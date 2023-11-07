# Preparing Programmatic Creation
01. Doing it the old way now
02. Commented out app-alert
03. Added a private showErrorAlert method to AuthComponent
04. Call it from the error argument on authObs.subscribe passing the errorMessage
05. Injected a ComponentFactoryResolver in AuthComponent
06. Assigned a const alertCmpFactory of type AlertComponent using ComponentFactoryResolver
07. Made a new PlaceholderDirective
08. Injected a public ViewContainerRef in it