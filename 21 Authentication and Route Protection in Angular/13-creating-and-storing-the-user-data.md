# Creating & Storing the User Data
01. Created a User model to store user data
02. Added a get method to get the private token for later
03. Created a user variable that is a Subject of type User
04. Used tap in pipe on the http requests to assign the response data to a new User
05. Called next on user passing the new user created in tap
06. Moved tap logic to a private method like we did with handleError