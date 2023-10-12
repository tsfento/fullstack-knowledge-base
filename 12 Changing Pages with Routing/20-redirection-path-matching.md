# Redirection Path Matching
01. The default matching strategy for routes is 'prefix'
02. That means it will check if the path STARTS with the path
03. '' would redirect every time because all paths start with '' or nothing
04. You can change the matching strategy to 'full' to counter this
05. { path: '', redirectTo: 'redirectPath', pathMatch: 'full' }