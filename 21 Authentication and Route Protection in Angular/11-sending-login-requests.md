# Sending Login Requests
01. Added a login method to AuthService
02. It uses a post request that is virtually identical (except the url) to the signup request
03. Added an authObs Observable to the onSubmit method in AuthComponent
04. Assign the request of login or signup to this authObs
05. Subscribe on authObs with repeated logic on our original requests keeping our code dry