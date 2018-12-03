# violet-seed

基于 Vue + Typescript + ElementUI 的种子工程（可供产品或项目使用）

## 1、主要技术栈

### 1.1 使用的三方组件

- [√] Vue 2 - 前端编程框架
- [√] Vue CLI 3 - Vue 构建脚手架
- [√] Typescript 3 - Javascript 超集
- [√] ElementUI 2 - 前端 UI 库
- [√] vue-class-component：6 - 支持基于 class 的 api 组件声明方式
- [√] vue-i18n：8 - 前端 vue 国际化组件
- [√] vue-property-decorator：7 - 在 vue-class-component 基础上提供了更多的装饰器
- [√] vue-router：3 - 路由组件
- [√] vuex: 3, - 状态管理器组件
- [√] vuex-class: 0.3 - 状态管理器-装饰器使用组件
- [√] axios：0.18 - http 访问组件
- [√] lodash：4.17 - 前端帮助库
- [√] date-fns: 2.0 - 前端日期处理帮助库
- [√] mocha: 5.2.4 - 单元测试框架
- [√] chai: 4.1.2 - 单元测试断言库

### 1.2 内部提供组件：

产品提供的基础组件库（可供产品或项目使用）  
 源码地址： `http://bitbucket.xxxxxxxxxxxx/projects/COMMON`  
 仓库地址：`http://xxxxxxxxxxxxxx:7002`

- [√] @gsafety/cad-gutil：2 - 基于项目特性封装的基础库：utilhelper、stringformat、sessionstorage、localstorage
- [√] @gsafety/rx-eventbus：2 - 基于 rx.js subject 特性封装的事件发布订阅组件
- [√] @gsafety/vue-httpclient：2 - 基于 axios 封装的 http 请求组件
- [√] @gsafety/cad-glog：2 - 基于 jsnlog 封装的日志组件，支持 console/send electron-main/remote url

## 2、使用规范文档

- [目录结构说明](./doc/01-工程结构.md)
- [日志记录方式](./doc/02-日志记录方式.md)
- [国际化使用方式](./doc/04-国际化.md)
- [静态代码质量检查](./doc/05-静态代码质量检查.md)
- [样式编程规范](http://confluence.gjsy.gsafety.com/pages/viewpage.action?pageId=8094479)
- [工程规范建议](./doc/03-工程规范建议.md)
- [单元测试-待补充](./doc/03-工程规范建议.md)
- [技术栈结构图](./doc/90-技术栈结构图.md)

## 3、安装

```
npm install
```

### 开发环境运行

```
npm run serve
```

### 生产环境 build

```
npm run build
```

### 运行 dist 目录-for 生产环境测试

`install http server`:

```
npm install -g serve
```

run:

```
serve  -s
```

### 运行测试

```
npm run test
```

### 静态代码质量检查

```
npm run lint
```

### 运行单元测试

```
npm run test:unit
```
