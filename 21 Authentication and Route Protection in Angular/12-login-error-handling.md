# Login Error Handling
01. Added a hanldeError private method in AuthService to run the same error logic on the signup and login request with catchError
02. Called that method from catchError instead
03. Added some switch cases to handle the login errors