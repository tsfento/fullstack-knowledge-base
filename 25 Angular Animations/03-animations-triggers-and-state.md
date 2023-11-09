# Animations Triggers and State
01. Animations are set up in the @Component decorator
02. Add an animations property with an array
03. Each animation has a trigger
04. trigger needs to be imported from angular/animations
05. trigger is a function whose first argument defines a name that when placed on the DOM will trigger an animation
06. You add the name to the div like [@divState]
07. You also need to bind a condition to determine which animation to run
08. [@divState]="state" where state is a variable in the component ts file
09. The second argument is an array
10. In the array you define your states
11. state is also imported from angular/animations
12. state is also a function with the first argument being the name of a state
13. The second argument uses style which is imported from angular/animations
14. style is a function that takes an object with your styles
15. For style properties with hyphens you can use them as a string