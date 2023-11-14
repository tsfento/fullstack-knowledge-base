# Adding a Component and some fitting Tests
01. Created a new UserComponent with the CLI
02. Made some divs that display depending on an ngIf condition
03. Added some variables to the UserComponent ts file
04. Cleared out most the spec file and started basically from scratch
05. Declared component in beforeEach using TestBed.configureTestingModule
06. If not using the CLI or if using any other webpack-based setup, you would need to add .compileComponents()
07. This is because the angular compiler would nut run in those instances
08. Added a test with an it block
10. Assigned variable fixture to TestBed.createComponent(UserComponent)
11. Assigned variable app to fixture.debugElement.ComponentInstance
12. Finally, called expect(app).toBeTruthy()
13. This simple test checks if the component is created