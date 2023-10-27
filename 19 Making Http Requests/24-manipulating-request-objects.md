# Manipulating Request Objects
01. You can also modify the request object in Interceptors
02. The request object itself is immutable
03. You will need to create a new variable and set it to req.clone
04. const modifiedRequest = req.clone({})
05. Return the modified request instead of original