# Using HostListener to Listen to Host Events
01. HostListener is decorate that can listen for events
02. It is added to methods in order to execute them
03. It must imported from @angular/core
04. @HostListener('eventname') methodName() { method logic }
05. @HostListnere('mouseenter') mouseOver() { changebackgroundcolor }
06. Can listen to events in the method mouseOver(eventData: Event)
07. Can be used mutliple times e.g. mouseenter and mouseleave