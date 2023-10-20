# Reactive: Grouping Controls
01. You can specify the path in the form get method
02. This is helpful because you might have a nested form in your typescript
03. You can nest a FormGroup in a FormGroup
04. Then wrap your HTML inputs in a div with formGroupName="userData"
05. You will need to update your validations
06. !signupForm.get('username').valid to !signupForm.get(.userData.username).valid