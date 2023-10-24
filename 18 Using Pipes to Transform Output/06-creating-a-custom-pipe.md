# Creating a Custom Pipe
01. Sometimes you need functionality that isn't built-in
02. You create pipes in a file
03. shorten.pipe.ts
04. You will export a class that implements PipeTransform
05. PipeTransform must be imported from angular/core
06. Every pipe must have a transform method with a return
07. You must also add the @Pipe decorator
08. In the decorator you can define the name for the pipe
09. @Pipe({ name: 'shorten' })