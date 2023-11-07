# Using ngIf
01. Added a close EventEmitter with Output to AlertComponent
02. Added click listeners to the button and backdrop div to call an onClose method
03. Emitted close in onClose method
04. Added close listener to app-alert on auth.component.html
05. It calls a new onHandleError method where error is reset to null