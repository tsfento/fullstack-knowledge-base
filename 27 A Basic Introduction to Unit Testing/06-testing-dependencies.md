# Testing Dependencies: Components and Services
01. Added a service to user folder
02. Added a user object with name property
03. Injected service in UserComponent and assigned user to service.user in ngOnInit
04. Added a test to check if UserComponent uses user.name from service
05. In test, assigned userService to fixture.debugElement.injector.get(UserService)
06. Must call fixture.detectChanges() before expect in order for component to update properties
07. Added a test to check if user.name is displayed in template if isLoggedIn is true
08. Copied most of code from previous test
09. Assigned compiled to fixture.debugElement.nativeElement to get the compiled template
10. expect(compiled.querySelector('p').textContent).toContain(app.user.name)
11. Assigned isLoggedIn to true before detectChanges
12. app.isLoggedIn = true
13. Added test to check opposite
14. Copied most of code from previous test
15. Removed isLoggedIn = true assignment
16. expect(compiled.querySelector('p').textContent).not.toContain(app.user.name)