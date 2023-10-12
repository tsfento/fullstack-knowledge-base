# Setting up Child (Nested) Routes
01. It is possible to have nested routes 
02. Declare child routes in the routes array in app.module
03. { path: 'path', component: CompName, children: [{ path: 'path', component: CompName } ]}
04. You need to add a router-outlet to the parent component to let angular know where to render it