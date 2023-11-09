# Example: Deploying to Firebase Hosting
01. ng build --configuration production will build your app for production
02. It will create a dist folder containing your compiled app
03. To use Firebase hosting, you need the Firebase CLI
04. npm install -g firebase-tools
05. Once installed, run firebase login to login to your account
06. Then firebase init to connect your app to one of your Firebase projects
07. Choose hosting from the list of options
08. Then choose the project you want to connect
09. Type your build directory when it asks for public directory
10. dist/build-directory
11. Answer yest to configuring as a single-page app
12. And no to overwriting the existing index.html
13. Finally run firebase deploy
14. After deploying you will be given a url where your app is now hosted