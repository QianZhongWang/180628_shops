# vue-demo

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

# vue项目

### 1.前台数据处理/交互/组件化

vue全家桶
- vue
- vue-router
- vuex
- mint-ui
- vue-lazyload

滑动库
- vue-scroller
- better-scroll
- swper

日期处理
- moment
- data-fns

### 前后台交互
- mock数据：mockjs
- 接口测试：postman
- ajax请求：vue-resource/axios

### 模块化
- es6
- babel

### 项目构建/工程化
- webpack
- vue-cli
- eslint

### css预编译器
- stylus


编码测试 
开发环境下运行  npm run dev  （在内存中对项目进行编译打包，在浏览器中运行）
生产环境下运行 
npm run build 生产环境下打包
npm install -g server 下载
server dist 打包后的文件生成在dist 文件夹中

项目用到stylus  需要下载stylus 和 stylus-loader    npm install stylus stylus-loader --save-dev
stylus 将stylus代码转译为css
stylus-loader webpack只能理解js模块