# Handling Errors
01. When interacting with servers, you are open to the chance of errors
02. There are different ways of handling errors
03. One way is the second argument in subscribe
04. subscribe(..., error => { console.log(error.message, error) })
05. Depending on the api, the error may give you beneficial data to relay to the user