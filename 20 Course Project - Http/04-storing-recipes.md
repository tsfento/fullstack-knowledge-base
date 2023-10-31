# Storing Recipes
01. Added a new storeRecipes method to DataStorageService
02. Injected RecipesService to get list of recipes
03. Used HttpClient put method to store and overwrite recipes in database
04. Important to know this is functionality Firebase allows, it may be different with other APIs
05. Handled subscription for request in own method since the header doesn't care about the response