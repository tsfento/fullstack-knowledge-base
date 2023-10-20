# Reactive: Creating a Custom Async Validator
01. Some validation may have to be requested from the server
02. This is asynchronous because the response does not happen typically instantly
03. Async Validators are set up the same as a regular Validator except the return a Promise or Observable
04. forbiddenEmails(control: FormControl): Promise<any> | Observable<any>
05. With a Promise, instead of returning you would resolve (or reject, i guess) your value
06. resolve({'emailIsForbidden': true}) or resolve(null);