在Webstorm上配置babel以后，每新建一个.js文件file watcher都会自动转换,
比如 entry.js，它的ES6 import语法转换为ES5 require语法，
但是在浏览器中并不支持require语法，因此需要 webpack entry.js entry-webpack.js 转换，html直接引用entry-webpack.js文件。