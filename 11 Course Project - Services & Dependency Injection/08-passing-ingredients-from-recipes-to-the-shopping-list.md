# Passing Ingredients from Recipes to the Shopping List (via a Service)
01. Added recipe service to recipe detail component
02. Created a method to be called when "to shopping list" clicked
03. Injected shopping list service into recipe service to access ingredients array
04. Created a method in shopping list service to pass ingredients from recipe and add them to the ingredients array. Then emit the new copy
05. Called shopping list method and passed recipe ingredients from recipe service