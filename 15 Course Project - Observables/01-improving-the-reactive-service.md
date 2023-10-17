# Improving the Reactive Service with Observables (Subjects)
01. Replaced ingredientsChanged EventEmitter in shopping-list.service with a Subject
02. Assigned ingredientsChanged to a Subscription in shopping-list.component
03. Unsubscribed from it in ngOnDestroy
04. Removed EventEmitter entirely from recipe-service
05. And the subscription in recipes.component