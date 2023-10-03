# Understanding the Component Lifecycle
01. ngOnInit is an example of a lifecycle hook
02. ngOnChanges is called after a bound input property changes
03. ngOnInit is called once the component is initialized
04. ngOnInit is run after the constructor
05. ngDoCheck is called during every change detection run
06. ngAfterContentInit is called after content (ng-content) has projected into view
07. ngAfterContentChecked is called every time the projected content has been checked
08. ngAfterViewInit is called after the component's view (and child views) has been initialized
09. ngAfterViewChecked is called every time the view (and child views) have been checked
10. ngOnDestroy is called once the component is about to be destroyed