# Building a Structural Directive
01. Made the opposite of ngIf for this example
02. @Input the condition to check against
03. Applied set to a method named the same as the selector to be executed when condition is changed
04. @Input() set appUnless(condition: boolean) {}
05. TemplateRef<any> is the template of the element appUnless is placed on
06. ViewContainerRef marks the location the directive is placed
07. Both must be imported from @angular/core 