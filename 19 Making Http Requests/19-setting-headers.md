# Setting Headers
01. Sometimes you need to send optional headers with your request
02. For instance, when the server looks for an authorization header
03. Any http request method has an argument for headers
04. this.http.get('url', { headers: new HttpHeaders({'Custom-Header': 'Hello'}) })
05. HttpHeaders must be imported from angular/common/http
06. HttpHeaders takes in an object with a custom key and value