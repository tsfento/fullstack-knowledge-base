# Binding to Directive Properties
01. Custom property binding works in directives
02. So does custome event binding, but will probably not be used often
03. Bind properties with @Input decorator
04. @Input() highlightColor: string = 'blue';
05. Can be overwritten in element
06. appBetterHighlight [hightlightColor]="'green'"