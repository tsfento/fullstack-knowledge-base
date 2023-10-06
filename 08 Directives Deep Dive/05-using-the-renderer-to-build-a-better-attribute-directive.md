# Using the Renderer to build a Better Attribute Directive
01. Directives can be generated like components in the CLI
02. ng g d directive-name --skip-tests true
03. Doing it this way updates the app.module.ts automatically
04. Accessing elements directly like in the last video is not good practice
05. Angular is able to render your templates without a DOM
06. So, these properties might not be available
07. Using the Renderer is a better practice
08. You must import Renderer2 and you can pass it in the constructor
09. constructor(private elRef: ElementRef, private renderer: Renderer2) {}