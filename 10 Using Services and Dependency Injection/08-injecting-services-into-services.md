# Injecting Services into Services
01. The highest level you can add a service is not the app component
02. It is the app module
03. Doing this allows the whole application to have access to the same instance of the service unless it is overridden
04. This must also be done to inject a service into another service
05. @Injectable decorator tells angular that something can be injected into the service
06. Must be imported from @angular/core
07. In newer versions of angular it is recommended to always add @Injectable
08. In the future it may be a good habit to have