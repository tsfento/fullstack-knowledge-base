# Understanding the Hierarchical Injector
01. Angular's dependency injector is a hierarchical injector
02. If we provide a service on one component, angular knows how to create an instance on the children, as well. Also, children of children and so on
03. The instance of the service only propagates down
04. Services override if placed on a higher level