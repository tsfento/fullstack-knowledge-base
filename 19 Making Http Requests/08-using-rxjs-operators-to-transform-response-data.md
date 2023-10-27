# Using RxJS Operators to Transform Response Data
01. You could transform data inside the subscribe method
02. But, it is good practice to use observable operators instead
03. We're using pipe and map again
04. Make sure to import map from rxjs
05. To convert the js object you get back you can loop through and push them
06. for (const key in responseData) { postsArray.push(responseData[key]); }
07. Making a new object while retaining the Firebase generated id will help keep track of the object
08. postsArray.push({ responseData[key], id: key });
09. It is good practice when using a for in loop to check if the data has the property you're looking for
10. if (responseData.hasOwnProperty(key))