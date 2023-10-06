# Creating a Basic Attribute Directive
01. Directives are created in a typescript file
02. They must import Directive from @angular/core
03. The one thing a directive absolutely needs is a selector
04. It should be a unique selector
05. You need to import the directive and add it to the declarations in app.module.ts
06. In the constructor, angular can pass the element the directive sits on by passing in the ElementRef
07. constructor(private elementRef: ElementRef)
08. Directives also have lifecycle hooks like ngOnInit
09. In this example the selector was in square brackets
10. This lets angular know we want to use it like an attribute