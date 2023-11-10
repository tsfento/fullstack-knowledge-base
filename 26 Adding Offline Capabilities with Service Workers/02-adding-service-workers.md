# Adding Service Workers
01. Javascript runs on a single thread attached to individual HTML pages
02. It also runs an additional thread, decouple from the HTML
03. This thread can run in the background, for example your browser on your mobile phone
04. It can also listen to outgoing network requests
05. Add the service worker by running
06. ng add @angular/pwa
07. This configures your existing project to use the service worker package and start with a preconfigured service worker
08. It adds a ServiceWorkerModule to the AppModule
09. It registers a service worker javascript file that is generated on build
10. When visiting the url of the app offline, you will still be able to see the hardcoded parts of the app, provided there is a cache