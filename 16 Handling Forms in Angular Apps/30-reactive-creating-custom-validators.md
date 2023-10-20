# Reactive: Creating Custom Validators
01. The built-in validators should cover most of your use-caes
02. But, you can also create customs ones
03. A Validator is just a function that gets called automatically when angular checks the validity of the FormControl
04. The function needs to receive the control to check
05. It also must return a javascript object
06. forbiddenNames(control: FormControl): {[s: string]: boolean} {}
07. Return {'shortErrorName': true} in your logic
08. Otherwise you must return null or omit the return altogether
09. You then add your validator to your control
10. 'username': new FormControl(null, [Validators.required, this.forbiddenNames]),
11. The above code will error, though, due to the way this is interpreted
12. You must bind 'this' as a workaround
13. this.forbiddenNames.bind(this)
14. if (this.forbiddenUsernames.indexOf(control.value) !== -1)
15. Without !== -1, the statement returns true because -1 is truthy