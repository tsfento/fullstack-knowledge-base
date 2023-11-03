# Adding an Auth Guard
01. Route guards allow you to run logic right before a route is loaded
02. Made a new AuthGuard service
03. Injected AuthService in AuthGuard
04. Returned this.authService.user, but fails because not a boolean
05. Used pipe with map to return !!user which is a boolean
06. Added the guard to recipes path
07. CanActivate can also return a UrlTree
08. This is useful for redirecting
09. Must add to return types
10. Check if !!user. If true, return true
11. Otherwise return this.router.createUrlTree(['/auth'])
12. Added take(1) to user subscription in AuthGuard to keep it from being an ongoing subscription