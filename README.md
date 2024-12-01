# Node.js Web Server Basic
Basic server with Node.js

```js
const http = require('http')
const fs   = require('fs')
const port = 8080

http.createServer(function (req, res) {
	
	res.writeHead(200,{'content-type':'text/html;charset=utf8'})

	res.end("test")
  
}).listen(port)

console.log(`Running at port ${port}`)
```
