# 安装

> 参考地址 [68课件网](http://www.68kejian.com/ ) [webpack中文网教程](http://webpackdoc.com/install.html)

首先要安装 [Node.js](https://nodejs.org/en/download/)， Node.js 最新的自带了软件包管理器npm（npm：包管理器） ，Webpack 需要 Node.js v0.6（注意：为了能支持es2015请下载4.0以上版本）

用 npm 安装 Webpack：

```bash
$ npm install webpack -g
```

此时 Webpack 已经安装到了全局环境下，可以通过命令行 `webpack -h` 试试。

通常我们会将 Webpack 安装到当前项目的依赖中，这样就可以使用项目本地版本的 Webpack。

```bash
# 进入项目目录
# 确定已经有 package.json，没有就通过 npm init 创建
# 如果没有写入权限，请尝试如下代码更改权限
# chflags -R nouchg .
# sudo chmod  775 package.json
# 安装 webpack 依赖
# --save-dev：向package.json中自动添加依赖项配置，无需手动配置
$ npm install webpack --save-dev

```


```
# 查看 webpack 版本信息
$ npm info webpack

# 安装指定版本的 webpack
$ npm install webpack@1.12.x --save-dev


```
> 运行：在node命令命令面板中输入

```bash

 webpack entry.js bundle.js  # 或者webpack ./entry.js ./bundle.js
```



