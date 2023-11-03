# Attaching the Token with an Interceptor
01. Adding an Interceptor to manipulate the requests instead of manually doing it each time
02. Moved user pipe to intercept method in AuthInterceptor
03. Modified the request with the auth params and returned the modified request
04. Added a check to see if user is null. If it is return the original request