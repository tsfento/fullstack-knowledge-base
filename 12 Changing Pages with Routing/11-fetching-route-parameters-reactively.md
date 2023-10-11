# Fetching Route Parameters Reactively
01. By default, Angular will not reload/recreate a component if you it is already rendered
02. You can subscribe to the params Observable on the route
03. this.route.params.subscribe();
04. It can take 3 arguments
05. The first is the most important
06. You can assign data from the params
07. this.user.id = params['id'];