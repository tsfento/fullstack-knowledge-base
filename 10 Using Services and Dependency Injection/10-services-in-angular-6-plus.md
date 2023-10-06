# Services in Angular 6+
01. Instead of adding a service class to the providers array in AppModule, you can set a config in @Injectable()
02. @Injectable({providedIn: 'root'}) export class MyService {...}
03. This new syntax is optional and the old way still works
04. It does offer one advantage that angular can load services "lazily" and redundant code can be removed automatically
05. This can lead to better performance and loading speed, but probably only noticed in bigger services or apps