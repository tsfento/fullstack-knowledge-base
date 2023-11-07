# Data Binding & Event Binding
01. Assigned the createComponent call to a const componentRef
02. componentRef has an instance property
03. Assigned componentRef.instance.message to message passed to showErrorAlert method
04. For close, made a closeSub Subscription to subscribe to the close EventEmitter
05. In the .subscribe method, unsubscribed and called hostViewContainerRef.clear()
06. Also added a check to see if closeSub is not null in ngOnDestroy
07. Unsubscribe if it isn't