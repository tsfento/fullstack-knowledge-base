# Fetching Recipes
01. Added fetchRecipes method to DataStorageService
02. Used HttpClient get method to fetch recipes from database
03. Handled subscription in own method since header doesn't care about the data and we have access to the RecipeService
04. Added a setRecipes method to RecipeService that passes a Recipe[]
05. Set this.recipes to Recipe[] and call recipesChanged.next to update subscribers
06. Set generic type of Recipe[] on get method to explicitly inform angular of the type of data we will receive