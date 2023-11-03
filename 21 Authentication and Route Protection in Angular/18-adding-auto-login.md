# Adding Auto-Login
01. Used setItem with localStorage in handleAuthentication method to store user object
02. Added an autoLogin method in AuthService
03. JSON.parse localStorage with 'userData'
04. Assign new loadedUser with data from 'userData'
05. If checked loadedUser.token to check if it is still valid
06. If it is, call next on User Subject passing loadedUser
07. Called autoLogin method from ngOnInit in AppComponent