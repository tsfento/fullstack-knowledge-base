# Protecting Routes with canActivate
01. Guards are a service
02. Can implement CanActivate interface
03. CanActivate forces you to use a canActivate method
04. canActivate receives 2 arguments (route: ActivatedRouteSnapshot, state: RouterStateSnapshot)
05. Angular provides the route and state
06. canActivate returns either an Observable, a Promise or a boolean
07. canActivate(): Observable: boolean | Promise<boolean> | boolean {}
08. With guards being a service, they can reach out to other services to get this information, as well
09. You can add the guard to the routes you want to guard by adding canActivate
10. { path: 'path', canActivate: [Guard], component: CompName }
11. Also applies to route children
12. Make sure your guard service and any other service you use is added to app.module