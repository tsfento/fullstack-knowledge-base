# Reactive: Using Error Codes
01. Angular adds the the error codes to the individual controls in the errors object
02. You can access the codes with the get method
03. signupForm.get('userData.username').errors['nameIsForbidden']
04. Will return true if the control contains the error 'nameIsForbidden'