# Using Relative Paths in Programmatic Navigation
01. The navigate method does not know which component you are on
02. routerLink knows the currently loaded rout
03. You can set the relative path as an argument
04. Inject ActivatedRoute like service or router
05. private route: ActivatedRoute (must be imported from angular/router)
06. this.router.navigate(['routeName'], { relativeTo: this.route })