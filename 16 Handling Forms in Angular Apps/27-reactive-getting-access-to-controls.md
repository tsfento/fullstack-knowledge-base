# Reactive: Getting Access to Controls
01. You can still use *ngIf to check validation on your controls
02. You don't use ngModel anymore, though
03. You directly access the form and call a get method with your control
04. *ngIf="!signupForm.get('username').valid && signupForm.get('username').touched
05. 