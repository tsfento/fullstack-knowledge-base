# Deleting Ingredients and Some Finishing Touches
01. Added a click listener to the Delete button on the ingredients list in RecipeEdit
02. Calls new method, onDeleteIngredient, passing the index
03. Used removeAt on ingredients FormArray to remove ingredient
04. Unsubscribed from recipesChanged in ngOnDestroy, but I already did this when I made the subscription