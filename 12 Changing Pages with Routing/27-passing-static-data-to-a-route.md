# Passing Static Data to a Route
01. Some routes will depend on data they receive statically or dynamically
02. You can use the data property on a route in the routes array to pass an object
03. { path: 'path', component: CompName, data: {key: 'value'} }
04. Get the date by this.route.snapshot.data['key']
05. Can also subscribe for changes
06. this.route.data.subscribe((data: Data) => {this.data = data['key']});
07. 