# Splitting Modules Correctly
01. Imported modules don't have access to the other modules in the parent module
02. Service modules like HttpClientModule are an exception
03. You can import the missing modules into the exported module
04. But, BrowserModule can only be used once in AppModule
05. In this case, you would import CommonModule