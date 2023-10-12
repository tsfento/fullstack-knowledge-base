# Resolving Dynamic Data with the Resolve Guard
01. The resolver will execute code just like canActivate and canDeactivate
02. It will not, however, decide whether a route can be rendered
03. It will always render the component, but will 'pre-load' some data
04. The Resolver is also a service
05. It must implement the Resolve interface
06. The interface must wrap the data type you want to fetch
07. implements Resolve<Server>
08. The Resolve interface requires to implement the resolve method
09. resolve(route: ActivatedRouteSnapshot, state: RouterStateSnapshot): Observable<Server> | Promise<Server> | Server {}
10. Must return one of the 3 options above
11. Add the resolve property to the route in the routes array
12. { path: 'path', component: CompName, resolve: {server: ServerResolver} }
13. Bind the data in your component by the same key ^ you used in the path