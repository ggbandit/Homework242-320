# Homework242-320
## เริ่มต้นคำสั่ง Hello World กับ Node.js
* เปิดโปรแกรม Node.js
* พิมพ์คำสั่งด้าน
```sh
var http = require('http');
http.createServer(function (req, res) {
    res.writeHead(200, {'Content-Type': 'text/plain'});
    res.end('Hello World!');
}).listen(8080);
```