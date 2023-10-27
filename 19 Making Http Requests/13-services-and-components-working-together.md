# Services and Components Working Together
01. You could create a Subject and subscribe to it to get the data
02. But, since only one component is interested, it is not ideal
03. A better solution is to return the request observable
04. You will need to subscribe to it in the component for it to work
05. this.postsService.fetchPosts().subscribe(posts => { });
06. The important thing to remember is that you should subscribe in the component versus the service if the component cares about the response and response status