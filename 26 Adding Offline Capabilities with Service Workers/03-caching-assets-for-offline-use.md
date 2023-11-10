# Caching Assets for Offline Use
01. The ngsw-config.json file is in the root of the app directory
02. It holds the configuration for your service worker
03. It is a javascript object containing an assetGroups array containing various configurations
04. In the resources object, you can add a "urls" array to cache assets like fonts from urls