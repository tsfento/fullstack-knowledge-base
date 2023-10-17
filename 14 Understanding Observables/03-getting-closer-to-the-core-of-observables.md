# Getting Closer to the Core of Observables
01. You will need to import from rxjs for observables
02. interval is an observable that functions like setInterval
03. interval(1000).subscribe(count => { console.log(count); });
04. Increments variable count every 1 second
05. It is important to unsubscribe from your custom observables to prevent memory leaks
06. Import Subscription from rxjs
07. You can assign your observable to a Subscription
08. this.firstObsSubscription = interval...
09. Implement OnDestroy
10. In ngOnDestroy you can call unsubscribe on your subscription
11. this.firstObsSubscription.unsubscribe();
12. You do not need to unsubscribe from built-in angular observables
13. Angular manages those itself