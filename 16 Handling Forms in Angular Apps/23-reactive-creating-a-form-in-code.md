# Reactive: Creating a Form in Code
01. You need to intialize the form before it is rendered
02. A good place for this is in ngOnInit
03. You initialize it by setting it to a new FormGroup
04. this.signupForm = new FormGroup()
05. FormGroup() takes in an object or objects with controls
06. this.signupForm = new FormGroup({ 'username': new FormControl(null), });
07. You can also pass default values instead of null
08. The key is quotation wrapped to make sure it is kept in minification