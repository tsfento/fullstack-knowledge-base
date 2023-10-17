# Understanding Operators
01. Operators are the magic feature of rxjs
02. Sometimes you don't want the raw data from your subscription
03. Operators can transform your data before you get it from the subscription
04. You import operators from rxjs
05. Operators are called from pipe() on your observable
06. observable.pipe(map());
07. map() takes a function as an argument
08. map((data: number) => { return 'Round: ' + (data + 1); })
09. Instead of regularly subscribing, you must subscribe to the pipe
10. observable.pipe(map(...)).subscribe(...);
11. filter is another operator
12. You can use multiple operators in pipe
13. They can chain and pass down or not