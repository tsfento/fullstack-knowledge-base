# Observing Different Types of Responses
01. Sometimes you need access to the either response object, not just the data
02. For example, to find out status code or get the headers
03. You add observe to the same argument with headers
04. post('url', body, { observe: 'response' })
05. observe can take a couple values (body is the default)
06. You can still access the body requesting it from the response
07. console.log(responseDate.body)
08. You can also observe events
09. { observe: 'events' }
10. Used the tap operator imported from rxjs to tap into the delete request and console logged the event
11. .pipe(tap(event => { console.log(event) }))
12. Can compare event.type to HttpEventType enum
13. Useful if you want to handle data depending on what type of event you receive