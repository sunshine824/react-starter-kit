# 基于React + Webpack + Babel的项目脚手架

> 这个脚手架工程模板用于快速启动基于 React + Webpack 为技术栈的前端项目

## Features 功能特性

- 可以解析 JSX 语法
- 可以解析 ES6 语法新特性
- 支持 LESS 预处理器
- 支持 fetch 请求
- 内置封装get/post请求
- 编译完成自动打开浏览器
- 区分开发环境和生产环境
- 实现组件级热更新
- 实现代码的热替换，浏览器实时刷新查看效果
- 分离业务功能代码和公共依赖代码
- 单独分离 CSS 样式文件
- 支持编译 HTML 模板
- 支持浏览器源码调试
- 支持一行命令产出待部署资源

## 1. start

```
$ git clone https://github.com/sunshine824/react-starter-kit.git
$ cd react-starter-kit
$ npm install
$ npm start
$ npm run build
```

查看效果` http://127.0.0.1:3000`


## 2.目录结构

```
    ├─package.json                                依赖库
    ├─README.md
    ├─src
    |  ├─App.js
    |  ├─index.js
    |  ├─registerServiceWorker.js
    |  ├─static                                   静态资源目录
    |  |   ├─README.md
    |  |   ├─css                                  css样式目录
    |  |   |  └base.css
    |  |   ├─js                                   js脚本库
    |  |   ├─images                               图片资源库
    |  ├─router                                   路由目录
    |  |   ├─README.md
    |  |   └routeMap.js
    |  ├─fetch                                    fetch接口请求目录
    |  |   ├─get.js                               get请求封装
    |  |   ├─post.js                              post请求封装
    |  |   ├─README.md
    |  |   └test.js                               测试接口
    |  ├─containers                               集成组件
    |  |     ├─README.md
    |  |     ├─Home
    |  |     |  ├─index.js
    |  |     |  └style.less
    |  ├─config                                   公共变量库
    |  |   └README.md
    |  ├─components                               微组件
    |  |     └README.md
    ├─scripts
    |    ├─build.js
    |    ├─start.js
    |    └test.js
    ├─public
    ├─config
```


## 3. 技术栈

- [x] [Webpack](https://webpack.github.io)
- [x] [React](https://facebook.github.io/react/)
- [x] [ES6](http://es6.ruanyifeng.com/)
- [x] [react-router-dom](https://reacttraining.com/react-router/)
- [x] [Babel](https://babeljs.io/)
- [x] [CSS modules](https://github.com/outpunk/postcss-modules)
- [x] [Less](https://github.com/less/less.js)
- [x] [Eslint](https://github.com/eslint/eslint)
