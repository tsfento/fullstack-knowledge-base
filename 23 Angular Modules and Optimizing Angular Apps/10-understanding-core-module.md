# Understanding the Core Module
01. The CoreModule is there to make the AppModule leaner
02. It holds Services that you then import into AppModule
03. An alternative would be to use providedIn: 'root' in Injectable on the Service, which is recommended
04. Interceptors will still need to be added to providers
05. Made a new CoreModule
06. Moved ShoppingListService, RecipeService and AuthInterceptor
07. You don't need to export these. By default they are provided app-wide