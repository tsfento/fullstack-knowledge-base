# Using Subjects for Error Handling
01. It's easy to react to an error in a subscription, but that's not always the case
02. You can make a Subject and pass the error with next from error argument wherever your subscribe method is
03. Then subscribe to the Subject in your component and handle the error there
04. Don't forget to unsubscribe in ngOnDestroy