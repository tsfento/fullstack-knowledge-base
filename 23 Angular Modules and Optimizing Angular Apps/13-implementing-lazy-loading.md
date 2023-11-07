# Implementing Lazy Loading
01. For lazy loading to work, your feature module needs to bring its own routes
02. Changed 'recipes' path in RecipesRoutingModule to ''
03. Added 'recipes' path back to AppRoutingModule
04. Instead of assigning a component to the route, we assign loadChildren
05. Takes a function () => import('./recipes/recipes.module').then(m => m.RecipesModule)
06. Remove RecipesModule from declarations in AppModule