# Getting Access to the Template & DOM with @ViewChild
01. @ViewChild can reference an element
02. @ViewChild('elementReference') elementReference: ElementRef;
03. Both ViewChild and ElementRef need to be imported from @angular/core
04. Example of access: elementReference.nativeElement.value
05. It is possible, but you should not change elements through ViewChild
06. Angular offers better ways of handling that