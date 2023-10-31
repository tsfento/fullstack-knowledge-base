# Fixing a Bug with the Resolver
01. Added a recipes variable assigned to RecipeService.getRecipes()
02. Add a conditional statement to check whether recipes.length === 0
03. If it is 0, we return the fetchRecipes
04. If it isn't, we return the recipe variable
05. Updated my deprecation solution to add a recipeResolver variable of type ResolveFn in the app-routing.module
06. It contains the above logic and I set resolve to it on the id paths