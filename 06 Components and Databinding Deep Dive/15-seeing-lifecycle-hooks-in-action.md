# Seeing Lifecycle Hooks in Action
01. It is good practice to be explicit about which interfaces or methods your component implements
02. export class ComponentName implements OnInit, OnChanges
03. ngOnChanges is the only hook that receives an argument
04. ngOnChanges(changes: SimpleChanges)
05. SimpleChanges must be imported from @angular/core
06. You will rarely use all of them, but some can be useful