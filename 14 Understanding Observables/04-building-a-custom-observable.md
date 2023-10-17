# Building a Custom Observable
01. To create a new observable, import Observable from rxjs
02. Observable used to have a create() method
03. It is now deprecated and the correct practice is to use 'new Observable'
04. const observable = new Observable((observer) => {})
05. Observable takes in a function that gets passed an observer by rxjs
06. The observer has some important methods
07. One is next() that emits a value
08. You subscribe to your observable the same way you subscribe to others
09. With subscription, you pass a function that accepts the data you are emitting
10. observable.subscribe(data => { console.log(data); });
11. Make sure you store your subscription and unsubscribe in ngOnDestroy