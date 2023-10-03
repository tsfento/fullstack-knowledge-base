# Passing Data with Event and Property Binding (Combined)
01. Assigned a click event to recipe-item to emit a custom event for the recipe
02. Added a custom event to recipe-list to pass the recipe that was selected
03. Listened to recipe-list event on recipes component and assigned the recipe to the $event
04. Added ngIf to app-recipe-detail selector to determine what recipe, if any, to display
05. Made an ng-template for the ngIf to reference if no recipe is selected
06. Added a Recipe property to the recipe-detail component
07. Used property binding to bind the recipe property to the selected recipe
08. Finally, used string interpolation to display the recipe name, description, and image