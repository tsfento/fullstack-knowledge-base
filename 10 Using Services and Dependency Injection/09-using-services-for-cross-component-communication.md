# Using Services for Cross Component Communication
01. You can use an EventEmitter in the service to enable communication between components
02. One can emit while the other subscribes to the event
03. this.accountsService.statusUpdated.subscribe((status: string) => alert('New Status: ' + status));