# Analyzing the Testing Setup (as created by the CLI)
01. The spec files we have been deleting/ignoring contain test parameters
02. In them, TestBed is imported from @angular/core/testing
03. Then you "describe" the "unit" to be tested
04. It contains a closure that is executed by the test runner
05. Each testing block is executed independently of the others
06. There is a "beforeEach" block at the beginning that is run before everything else
07. In it is TestBed.configureTestingModule that declares which components you want in the testing environment
08. After that are the tests as "it" blocks
09. They create an instance of the component and assign it to a variable (fixture) to be tested
10. Another variable (app) is assigned to fixture.debugElement.someMethod
11. Finally, there is an expect method that the test package will check