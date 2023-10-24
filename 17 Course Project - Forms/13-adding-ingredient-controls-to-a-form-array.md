# Adding Ingredient Controls to a Form Array
01. Added a ingredients FormArray to initForm and intialized it with an empty array
02. Checked if recipe has ingredients if in editMode
03. If so, pushed those as a FormGroup to our FormArray
04. Assigned FormArray to recipeForm
05. Added formArray directive to the ingredients section of the form
06. Used ngFor to loop through the ingredients in the FormArray
07. Assigned formControlNames to the inputs