# Ahead-of-Time Compilation
01. Whereas typescript code is compiled to javascript for the browser,
02. There is an angular compiler in the process to compile the template syntax to javascript DOM instructions
03. This is Just-in-Time (JiT) compilation
04. The angular compiler runs in browser at runtime
05. This can be changed during build to Ahead-of-Time (AoT) Compilation
06. Here, the angular compiler runs during build and not the browser
07. ng serve, by default, uses the jit compiler
08. ng build --prod builds your app using aot compilation
09. Actually, ng build --configuration production now