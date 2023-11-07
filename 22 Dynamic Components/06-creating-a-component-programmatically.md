# Creating a Component Programmatically
01. Added an ng-template to auth.component.html
02. Added the appPlaceholder directive to it
03. Added ViewChild of type PlaceholderDirective to AuthComponent
04. Made a const hostViewContainerRef in showErrorAlert method
05. Assigned it to PlaceholderDirective's ViewContainerRef
06. Called hostViewContainerRef.clear() to make sure the placeholder is empty
07. Used hostViewContainerRef's create method to pass in alertCmpFactory