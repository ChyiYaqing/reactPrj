# reactPrj
learn react course (from frecodecamp.org)

> React 是用于构建用户界面的JavaScript库.



## 常见问题

1. Access to XMLHttpRequest at 'file:////reactPrj/index.js' from origin 'null' has been blocked by CORS policy: Cross origin requests are only supported for protocol schemes: http, data, isolated-app, chrome-extension, chrome, https, chrome-untrusted.

```
The `file://` protocol does not work with CORS - only a certain set of them work, such as `http://`

For local development you could serve the files with a simple web server.

With Python 2.7 installed, go into the folder where your project is served, like `cd reactPrj/`. and then use `python -m SimpleHTTPServer` which would make `index.html` and it's JavaScript files available at `localhost:8000`

For Python3 use `python -m http.server`

```
