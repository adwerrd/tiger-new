# tiger-new

快速生成一个标准开发项目的 CLI。(本项目自 facebook 官方出品的 [create-react-app](https://github.com/facebookincubator/create-react-app) 修改而来)

* CLI-QA 形式初始化配置项目
* 生成的项目支持 webpack + es6 开发环境
* 支持 `Service Worker Precache`，生成离线应用
* 也支持 jsx 语法，所以也同时可以用来开发 react 应用
* 不仅支持 SPA，也支持多页面项目开发
* 多页面应用支持模板分离
* 打包构建支持抽取打包公共组件、库、样式
* 支持 scss、less
* 支持 eslint 语法检查
* 支持 ternjs 配置

更多特性及使用细节请安装后创建项目查看

![screenshot](https://cloud.githubusercontent.com/assets/3774036/26042794/b2ee8ce0-396a-11e7-97e1-b52f31309c2c.png)

## v2.x 新功能

* 持久化缓存的优化
* webpack 升级到 2.x
* webpack-dev-server 的升级，带来更好的 proxy 支持

## FAQ
* ~~[好像不支持decorators特性，如何支持？](https://github.com/qiqiboy/tiger-new/issues/4#issuecomment-377101352)~~
 从`v2.9.4`开始，生成项目时支持选择是否需要支持装饰器特性。

## 安装

    $ npm install tiger-new -g

## 使用

#### 创建新项目

    $ tiger-new <项目名|路径>

#### 升级老项目

    $ tiger-new <项目名|路径> --upgrade

例如：

    $ tiger-new my-new-project
    $ cd my-new-project/
    $ npm start
