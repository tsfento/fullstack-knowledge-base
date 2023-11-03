# Preparing the Signup Request
01. Went through the Firebase documentation to see how to format the sign up request
02. https://firebase.google.com/docs/reference/rest/auth#section-create-email-password
03. Added a new AuthService to handle the requests
04. Injected HttpClient into AuthService
05. Added a signup method to AuthService
06. It uses a post request to the Firebase url with an api token
07. The body of the request is a javascript object that conforms to the documentation
08. Added an interface to structure the response we will get from the request
09. Assigned interface as generic type to post request