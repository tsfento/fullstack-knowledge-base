# Passing Query Parameters and Fragments
01. You can use queryParams to pass params to routerLink
02. [queryParams]="{allowEdit: '1'}"
03. There is also fragment
04. fragment="loading"
05. Both can also be passed in navigate
06. this.router.navigate(['/servers', id, 'edit'], {queryParams: {allowEdit: '1'}, fragment: 'lodaing'});