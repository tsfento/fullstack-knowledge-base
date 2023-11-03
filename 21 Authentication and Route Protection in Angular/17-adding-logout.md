# Adding Logout
01. For logging out we just call next on the User Subject and pass it null
02. Created method for this in AuthService
03. Call it from HeaderComponent on click of logout
04. Injected Router in AuthService and added navigation to auth in logout method