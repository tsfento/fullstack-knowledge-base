# Using Types with the HttpClient
01. By default, angular has no idea the type of data it receives
02. You can explicitly define it, though
03. map((responseData: { [key: string]: Post }) => { })
04. Doing this makes for cleaner code and provides benefits with autocompletion
05. An easier way with HttpClient is assigning to get method (generic)
06. .get<{ [key: string]: Post }>()
07. Also available on post and other http methods
08. This is entirely optional, but recommended