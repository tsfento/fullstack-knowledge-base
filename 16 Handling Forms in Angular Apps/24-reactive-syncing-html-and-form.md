# Reactive: Syncing HTML and Form
01. By default, angular will autodetect a form and create one for you
02. In the reactive approach, this is not what you want
03. You will need to add some directives to override this behavior
04. Adding the [formGroup] property binding tells angular to use your form instead of creating one
05. [formGroup]="signupForm"
06. Use the formControlName directive on your input to tell angular which control it is in your typescript form
07. formControlName="username"