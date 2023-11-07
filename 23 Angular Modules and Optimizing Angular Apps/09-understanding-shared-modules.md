# Understanding Shared Modules
01. Shared modules would be a good use for holding components that are shared among multiple feature modules
02. Made a SharedModule
03. Moved AlertComponent, LoadingSpinnerComponent, PlaceholderDirective, DropdownDirective and CommonModule
04. Exorted these
05. Imported SharedModule in place of CommonModule in RecipesModule and ShoppingListModule
06. Also imported into AppModule