# Errors & Completion
01. You will handle data with a function in a subscription more often than not
02. HTTP requests have a possibility of erroring and you need to handle these
03. On subscribe, the second argument gets called when an error is thrown
04. obs.subscribe(data => {}, error => {});
05. The third argument is called on completion
06. obs.subscribe(data => {}, error => {}, () => {});
07. This function has no arguments because completing doesn't pass arguments
08. You technically don't need to unsubscribe if your observable completes or errors
09. Error is not the same as completing
10. An error cancels the observable, it does not complete it