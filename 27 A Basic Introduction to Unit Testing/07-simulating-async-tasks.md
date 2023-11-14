# Simulating Async Tasks
01. Added a DataService to shared folder
02. Added a getDetails method to it that makes a promise that resolves 'Data' after 1500 milliseconds using setTimeout
03. Injected DataService in UserComponent
04. Made a non async test to check that data should not be fetched
05. In it, added fixture, app, and dataService
06. Assigned variable (spy) to spyOn(dataService, 'getDetails')
07. Chained .and.returnValue(Promise.resolve('Data')); to spy
08. fixture.detectChanges()
09. expect(app.data).toBe(undefined)
10. Made a test to check that data should be fetched
11. Copied code from previous test
12. Max uses async, but it's deprecated
13. Now use waitForAsync, but everything else is the same
14. After detectChanges, added fixture.whenStable().then( see below )
15. Moved expect inside then, () => { expect(app.data).toBe('Data') }