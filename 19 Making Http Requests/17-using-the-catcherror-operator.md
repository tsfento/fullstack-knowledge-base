# Using the catchError Operator
01. No matter how you handle your error, the catchError operator can be useful
02. You can call catchError as the second argument in your http response method
03. this.http.get('url').pipe(map(response => {}), catchError(errorRes => {}))
04. Max imports throwError and uses it, but it has been deprecated
05. return throwError(errorRes);
06. rxjs docs suggests: throw new Error(errorRes)
07. Could also throw new Error(errorRes.message)
08. Whatever you want to pass