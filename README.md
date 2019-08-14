# 项目技术介绍
## Taro + webpack（Taro内置） + scss + TypeScript
## Taro：
> [Taro](https://taro.aotu.io/)：是一套遵循 [React](https://react.docschina.org/) 语法规范的 多端开发 解决方案。使用 Taro，我们可以只书写一套代码，再通过 Taro 的编译工具，将源代码分别编译出可以在不同端（[微信](https://mp.weixin.qq.com/)/百度/支付宝/字节跳动/QQ小程序、快应用、H5、React-Native 等）运行的代码。
## webpack：
> [webpack](https://www.webpackjs.com/)：JavaScript 应用程序的静态模块打包器(module bundler)
## scss：
> [scss](https://www.sass.hk/)：一款强化 CSS 的辅助工具，它在 CSS 语法的基础上增加了变量 (variables)、嵌套 (nested rules)、混合 (mixins)、导入 (inline imports) 等高级功能，这些拓展令 CSS 更加强大与优雅。使用 Sass 以及 Sass 的样式库（如 Compass）有助于更好地组织管理样式文件，以及更高效地开发项目。
## TypeScript：
> [TypeScript](https://www.tslang.cn/)：javascript的超集，包含javascript的所有特性，可以编译成javascript，支持强类型检查

# 项目目录介绍

```
├── config                 配置目录
|   ├── dev.js             开发时配置
|   ├── index.js           默认配置
|   └── prod.js            打包时配置
|
├── dist                   项目编译后的目录，yarn dev:weapp 自动生成
|
├── node_modules           项目依赖文件目录，yarn install 自动生成
|   
├── src                    源码目录
|   ├── components         公共组件目录
|   ├── pages              页面文件目录
|   |   ├── index          index 页面目录
|   |   |   ├── banner     页面 index 私有组件
|   |   |   ├── index.js   index 页面逻辑
|   |   |   └── index.css  index 页面样式
|   ├── utils              公共方法库
|   ├── app.css            项目总通用样式
|   └── app.js             项目入口文件
└── package.json           项目依赖书
```


# 小程序启动方式
## 下载依赖
> yarn install

## 项目启动
>yarn dev:weapp

## 编译项目
>yarn build:weapp
