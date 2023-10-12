# Controlling Navigation with canDeactivate
01. You can also control whether a user can leave a route
02. Use case: if a user modified something without saving and tried to navigate away
03. Made can-deactive-guard.service.ts that exports the interface CanComponentDeactivate
04. The interface forces the component to have a canDeactivate method
05. Also exports the class service itself (CanDeactivateGuard) that implements CanDeactivate
06. CanDeactivate can wrap your own interface
07. implements CanDeactivate<CanComponentDeactivate> {}
08. Implement canDeactivate method
09. canDeactivate(comp: CanComponentDeactivate, curRoute: ActivateRouteSnapshot, curState: RouterStatSnapshot, nextState?: RouterStateSnapshot): Observable<boolean> | Promise<boolean> | boolean {}
10. Then return comp.canDeactivate(); in the method
11. Add property to path in routes array
12. { path: 'path', component: CompName, canDeactivate: [CanDeactiveGuard] }
13. Make sure to add guard to providers app.module
14. Implement the CanComponentDeactivate interface on component and add a canDeactivate method to handle your logic