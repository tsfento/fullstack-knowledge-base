# Allowing the Deletion of Shopping List Items
01. Added a click listener to Delete button
02. Calls onDelete method in ShoppingEdit
03. Added a deleteIngredient method to ShoppingListService
04. Takes in index of ingredient and splices it out
05. Call deleteIngredient method from onDelete passing in editedItemIndex
06. Call onClear method after to clear the form
07. Added ngIf to Delete button to only show if editMode is true