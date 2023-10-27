# Introducing Interceptors
01. A use case for Interceptors would be if you want to attach a certain param or header to every outgoing request
02. An Interceptor is basically a service
03. It implements HttpInterceptor which must be imported from angular/common/http
04. Requires an intercept method
05. The intercept method gets 2 arguments
06. The first is an HttpRequest object which must be imported
07. It is a generic object so use <> to inform what data the request will yield
08. The second is HttpHandler...import it
09. HttpHandler has a handle method to pass the HttpRequest object
10. intercept(req: HttpRequest<any>, next: HttpHandler) { logic return next.handle(req); }
11. Your logic is run right before the request leaves the app and then, still, let the request leave
12. Must provide the service in a different way
13. Add a js object to providers in app.module
14. { provide: HTTP_INTERCEPTORS, useClass: AuthInterceptorService, multi: true }