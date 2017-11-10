# Node_begin1
Node环境搭建

一、
创建node.test.js(e:\node)

test.js

var http = require("http");//http模块
http.createServer(function(req,res){
	res.writeHead(200,{"Content-Type":"text/html"});
	res.write("node.js");
	res.write("<p>Hello World</p>");
	res.end("<p>lishui365.com</p>");
}).listen(3000);//监听3000端口
console.log("HTTP server is listening at port 3000.");
```
二、
dos窗口，
cd e:\node
node test.js

三、
浏览器访问：http://localhost:3000/
