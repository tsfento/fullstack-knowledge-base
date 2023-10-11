# An Important Note about Route Observables
01. Angular cleans up the component in the background when it is destroyed
02. The subscription remains
03. You can assign the subscription to a variable and unsubscribe OnDestroy
04. It is not required, though
05. You do need to unsubscribe from your own custom subscriptions