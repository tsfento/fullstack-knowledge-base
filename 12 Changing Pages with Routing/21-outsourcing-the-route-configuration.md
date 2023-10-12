# Outsourcing the Route Configuration
01. If your routes array becomes too large to contain in the app.module, you can outsource the routes to a new module
02. Make a new module: export class NameModule, import NgModule from angular/core
03. Add the @NgModule decorator
04. Place your routes array in the module (maybe above the decorator)
05. Add imports to the decorator
06. imports: [RouterModule.forRoot(routesArray)]
07. And add an export for the RouterModule exports: [RouterModule]
08. Make sure you have all imports at the top