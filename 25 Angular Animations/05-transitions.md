# Transitions
01. Adding the transition method to trigger array
02. transition is a function and needs to be imported from angular/animations
03. The first argument is the starting state => ending state
04. transition('normal => highlighted')
05. The second argument takes animate which needs to be imported
06. The first argument in animate is the time in milliseconds the animation should take
07. You can add additional transitions for reversing for example
08. transition('highlighted => normal', animate(300))