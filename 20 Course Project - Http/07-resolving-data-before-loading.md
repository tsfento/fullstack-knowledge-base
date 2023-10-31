# Resolving Data Before Loading
01. Added a resolver to solve bug when direct accessing recipe detail with the url path
02. Created new RecipeResolverService
03. Removed subscribe from fetchRecipes in DataStorageService
04. Added tap to it where we call the setRecipes method and return the get request
05. Subscribed with arguments to fetchRecipes in onFetchData in the header
06. Added the resolver to the paths that use recipe id
07. This way angular runs the resolver before loading the route fetching the recipe
08. Resolve is deprecated and will be removed in Angular 17
09. Couple of different ways to handle this
10. The one I chose was to directly inject the DataStorageService in the resolve argument of the route
11. resolve: { data: () => inject(DataStorageService).fetchRecipes() }