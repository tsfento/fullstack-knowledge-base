# Adding a Loading Spinner & Error Handling Logic
01. Made a new LoadingSpinnerComponent
02. Copied CSS from loading.io/css to loading-spinner.component.css
03. Copied HTML from loading.io/css to template in loading-spinner.component.ts
04. Added component to html and used ngIf to hide form and display spinner while isLoading is true
05. Added an isLoading boolean to AuthComponent
06. Set isLoading to true before request and set to false after response is received
07. Added an error string variable
08. Assigned the value from the response error
09. Made a new div to display the error to the user using ngIf if error is not null