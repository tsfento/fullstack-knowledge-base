# Sending a POST Request
01. You need to import the HttpClientModule from angular/common/http in your app.module
02. Use dependency injection in your component to use it
03. private http: HttpClient
04. HttpClient will need to be imported in your component
05. HttpClient has methods that are mostly named like the Http verbs
06. The post method's first argument is the url
07. In a real world application, you would have clearly defined endpoints such as posts/add
08. Firebase takes those segments and adds them as folders in the database
09. For Firebase, you need to add .json to your segment
10. post also requires a body
11. Normally, you will send json data when interacting with a resftul api
12. Angular's HttpClient automatically converts to json for you
13. In angular, http requests are managed by observables
14. If there is no subscriber to the http request, angular (and rxjs) will not send the request
15. post returns an observable that wraps your request
16. To get access to the response, you must call subscribe
17. this.http.post('url', bodyData).subscribe(responseData => { your logic });
18. You don't need to manage the subscription by unsubscribing since it is an observable provided by angular
19. When sending POST requests, 2 requests are sent
20. The first is OPTIONS to check if a POST request is allowed
21. If successful, your actual POST request will...post