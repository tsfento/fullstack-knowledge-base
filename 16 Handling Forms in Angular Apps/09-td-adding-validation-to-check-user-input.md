# TD: Adding Validation to check User Input
01. While you should still validate input on the server, you can enhance the UX by adding validation to the form itself
02. Adding the required attribute let's angular know the input is invalid if empty
03. required is a built-in HTML attribute but treated as a selector in angular
04. email is directive to let angular check if it's a valid email
05. If submitted without meeting the criteria, the valid property will be false
06. Angular also adds classes to the form on input
07. ng-dirty, ng-touched, ng-valid, ng-invalid, etc.
08. These can be used to style the form