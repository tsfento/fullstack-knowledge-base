# TD: Setting and Patching Form Values
01. Accessing the form with @ViewChild, you can call .setValue() to pass an object the same type as the form
02. This will override all user inputs, though
03. formName.form.patchValue() will set the value for only data specified
04. this.formName.form.patchValue({ userData: { username: suggestedName }});