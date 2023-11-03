# Reflecting the Auth State in the UI
01. Injected Router in AuthComponent to navigate to recipes when user authenticates
02. Injected AuthService in HeaderComponent
03. Subscribed to AuthService user in ngOnInit in HeaderComponent. Unsubscribed in ngOnDestroy
04. Made an isAuthenticated boolean to check when user is not null in subscription
05. Used ngIf with isAuthenticated to show and hide elements in the HeaderComponent template