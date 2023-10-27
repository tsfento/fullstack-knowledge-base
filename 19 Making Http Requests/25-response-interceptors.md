# Response Interceptors
01. You can also interact with the response in Interceptors
02. handle is an observable so you can use things like pipe with it
03. You always get an event with an Interceptor
04. return next.handle(modifiedRequest).pipe(tap(event => { logic }))