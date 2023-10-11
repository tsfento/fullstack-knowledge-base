# Setting up and Loading Routes
01. The app module is where you should register your routes
02. Routes should be in an array in the app module
03. You will need to import from Routes from angular/router
04. const appRoutes: Routes = [{ path: 'routeName', component: ComponentName }];
05. localhost:4200/routeName
06. Must register routes in imports
07. Import RouterModule from angular/router
08. RouterModule.forRoot(appRoutes)
09. Declare where you want route by using the directive <router-outlet> like loading a component