# TD: Submitting and Using the Form
01. Angular takes advantage of the submit type on a button in a form
02. It gives a directive, ngSubmit, you can place on the form element
03. (ngSubmit)="someMethod()"
04. In the TD approach, everything in the form is done in the template
05. In order to get the form you can place a local reference and pass it to the ngSubmit method
06. <form (ngSubmit)="someMethod(f)" #f>
07. To get the javascript object of the form, you must set the reference to ngForm
08. #f="ngForm"
09. ngForm must be imported in the class ts file