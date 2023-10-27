# Adding Query Params
01. For many api endpoints you can also attach certain query parameters
02. You add params in the same object you added headers
03. { headers: new HttpHeaders({...}), params: new HttpParams }
04. Must also import HttpParams
05. You call set() from params and set a param name and value
06. params: new HttpParams().set('print', 'pretty')
07. If you have a large number of params you can store them in a variable
08. let searchParams = new HttpParams();
09. The variable is immutable so a new one is created every time you append to it
10. searchParams = searchParams.append('print', 'pretty');