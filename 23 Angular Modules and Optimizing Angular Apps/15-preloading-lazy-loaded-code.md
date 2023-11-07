# Preloading Lazy-Loaded Code
01. You can add a second argument to RouterModule.forRoot in AppRoutingModule
02. It's an object that contains a preloadingStrategy property
03. { preloadingStrategy: PreloadAllModules }
04. This lets angular preload modules to make navigation faster while still lazy loading