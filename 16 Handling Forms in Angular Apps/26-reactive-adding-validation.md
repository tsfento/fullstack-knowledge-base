# Reactive: Adding Validation
01. You're not configuring the form in the HTML template
02. You're only synchronizing it with the directives
03. The second argument on FormControl is for validators
04. Import Validators from angular/forms
05. 'username': new FormControl(null, Validators.required),
06. You can also pass an array of multiple Validators
07. 'email': new FormControl(null, [Validators.required, Validators.email]),