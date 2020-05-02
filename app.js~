var http = require('http');
http.createServer(function(req, res) {
  res.writeHead(200, {
    'Content-Type': 'text/html'
  });
  res.write('<!doctype html>\n<html lang="en">\n' + 
    '\n<meta charset="utf-8">\n<title>Test web page on node.js</title>\n' + 
    '<style type="text/css">* {font-family:arial, sans-serif;}</style>\n' + 
    '\n\n<h1>DevOps Test</h1>\n' + 
    '<div id="content"><p>This is test application</p><ul><li>Docker</li><li>Node</li><li>Git</li></ul></div>' + 
    '\n\n');
  res.end();
}).listen(8080, '0.0.0.0');
console.log('Server running at http://0.0.0.0:8080');
