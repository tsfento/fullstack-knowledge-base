# Multiple Interceptors
01. The order you add Interceptors matters
02. The will execute in the order they are provided
03. Add additional Interceptors right after each other in app.module
04. { Interceptor 1}, { provide: HTTP_INTERCEPTORS, useClass: InterceptorClass, multi: true }