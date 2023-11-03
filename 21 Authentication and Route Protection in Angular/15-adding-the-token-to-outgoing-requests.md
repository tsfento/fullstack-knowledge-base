# Adding the Token to Outgoing Requests
01. Changed User Subject in AuthService to BehaviorSubject
02. This subject gives access to the data even if the subscription happens after the data has been emitted
03. Must be import from rxjs
04. Takes an argument. We passed null for now
05. Subscribed to user in fetchRecipes in DataStorageService
06. Used take operator from rxjs in pipe before subscribe
07. It takes a number, the number of values you want from the observable, and automatically unsubscribes
08. Added exhaustMap operator to pipe on the user subscription
09. This operator waits for a first observable to complete
10. Then it returns a new observable replacing the first
11. Moved the http request into exhaustMap
12. Moved map and tap from the http request in the pipe method containing the request
13. Then returned the whole observable in the method
14. With Firebase realtime databases, you pass a token with a query parameter in the url
15. Added a second argument to the request url to pass an object with params
16. Added a new HttpParams().set('auth', user.token)