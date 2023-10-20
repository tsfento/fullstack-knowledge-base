# Reactive: Arrays of Form Controls (FormArray)
01. You can have an array of controls in your FormGroup
02. 'hobbies': new FormArray([]),
03. You must import FormArray from angular/forms
04. You can push controls in the array, but you must cast the array to push
05. (<FormArray>this.signupForm.get('hobbies')).push(FormControl you setup)
06. You synchronize it with the form with formArrayName="hobbies"
07. There is an updated way to iterate through your controls in the array
08. See the notes here: https://pro.academind.com/courses/765847/lectures/13902801