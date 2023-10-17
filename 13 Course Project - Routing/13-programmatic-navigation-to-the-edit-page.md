# Programmatic Navigation to the Edit Page
01. Added click events to the new and edit buttons
02. These call methods that use router.navigate to change the url
03. this.router.navigate(['new'], { relativeTo: this.route });
04. this.router.navigate(['edit'], { relativeTo: this.route });