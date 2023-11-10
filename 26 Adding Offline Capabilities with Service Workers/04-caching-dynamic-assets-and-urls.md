# Caching Dynamic Assets & URLs
01. Added a new configuration group called dataGroups to ngsw-config.json
02. assetGroups are for assets, dataGroups are for data
03. Typically, data you request from an API or data that might change frequently
04. It is an array of objects just like assetGroups
05. You assign a name and an array of urls
06. There is a version property if your API supports it
07. You can add a cacheConfig which is an object that configures how the data should be cached
08. You can add a maxSize property that determines how many entries to cache
09. Or, how many responses
10. Also, maxAge to define how old should the cache data be before fetching new data
11. maxAge is assigned a string like "1d", "12h" or "50m"
12. timeout defines a time to wait before using the cached data
13. Finally, there is strategy
14. It has 2 options, freshness and performance
15. freshness means always reach out to the backend and only use cache if offline
16. performance tries to get something on the screen as soon as possible
17. performance takes maxAge into account while freshness takes timeout