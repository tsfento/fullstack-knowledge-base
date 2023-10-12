# Understanding Location Strategies
01. Routes might not work the same way as when using localhost for testing
02. The dev server has a special configuration your actual server will also need
03. It has to return the index.html file on 404 error
04. You can fall back to # hash signs
05. This informs your server to only care about the url before the hash
06. This is helpful if the non-hash mode doesn't work