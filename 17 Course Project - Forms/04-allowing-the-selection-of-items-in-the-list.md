# Allowing the Selection of Items in the List
01. Added a click listener to the indgredients in the form
02. This calls the method onEditItem which passes the index from ngFor
03. Made a new Subject in ShoppingListService to denote when editing
04. Called next with the Subject in onEditItem to pass the index
05. Subscribed to the Subject in ShoppingEdit
06. Set up a boolean for editing and passed the index for the item