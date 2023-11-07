# Adding Routes to Feature Modules
01. You can also move routes to another module
02. Made a new RecipesRoutingModule
03. Moved recipes route from AppRoutingModule
04. Added RouterModule.forChild(routes) to imports passing in routes
05. Added RouterModule to exports
06. Since AppModule imports RecipesModule, it sees the routes