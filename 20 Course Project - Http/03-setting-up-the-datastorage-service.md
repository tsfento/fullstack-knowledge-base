# Setting Up the DataStorage Service
01. The links for saving and fetching data are in the header component
02. One way of handling our task would be to add click listeners and inject the HttpService in the header component and do our requests there
03. This has a couple of disadvantages, though
04. One being, the header component does not have the data
05. That data is in the RecipeService
06. We could make the requests there, but it might be a good idea to separate it for cleaner maintainable code
07. Created new data-storage.service
08. Imported HttpClientModule in app.module
09. Injected HttpClient in DataStorageService