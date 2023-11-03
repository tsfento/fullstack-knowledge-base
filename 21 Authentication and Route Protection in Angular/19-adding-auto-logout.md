# Adding Auto-Logout
01. Removed 'userData' from localStorage in logout method in AuthService
02. Added autoLogout method that takes an expirationDuration number as an argument
03. Added a setTimeout that runs logout when expirationDuration is over
04. Assigned setTimeout to a variable to call clearTimeout when logout method is called in case user manually logs out
05. Called autoLogout after calling next on User Subject in handleAuthentication and autoLogin