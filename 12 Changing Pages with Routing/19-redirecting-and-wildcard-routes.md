# Redirecting and Wildcard Routes
01. Instead of a component, you can pass a redirect on a route
02. { path: 'path', redirectTo: '/redirectPath' }
03. ** is the wildcard route
04. { path: '**', redirectTo: '/redirectPath' }
05. It will catch all non-defined routes
06. Routes are parsed from first to last, so make sure it is the last route in the array