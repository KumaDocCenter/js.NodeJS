# 安装后如何从Node.js开始？

安装Node之后，让我们尝试构建我们的第一个Web服务器。创建名为“app.js”的文件，并粘贴以下代码： 

```javascript
const http = require('http');

const hostname = '127.0.0.1';
const port = 3000;

const server = http.createServer((req, res) => {
  res.statusCode = 200;
  res.setHeader('Content-Type', 'text/plain');
  res.end('Hello World\n');
});

server.listen(port, hostname, () => {
  console.log(`Server running at http://${hostname}:${port}/`);
});
```



之后，运行您的Web服务器`node app.js`，访问[http：//localhost：3000](http://localhost:3000/)，您将看到一条消息“Hello World” 