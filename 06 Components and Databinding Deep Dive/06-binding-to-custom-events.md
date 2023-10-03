# Binding to Custom Events
01. Custom events can be created with EventEmitter
02. event = new EventEmitter<templateForData>>();
03. this.event.emit(dataToEmit);
04. @Output to make it bindable to parent components
05. Must import both from @angular/core