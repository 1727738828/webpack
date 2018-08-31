### 1，本地安装
### 2，全局安装

#### 一，本地安装
要安装最新版本或特定版本，请运行以下命令之一

```
npm install --save-dev webpack
npm install --save-dev webpack@<version>
```
使用 webpack 4+ 版本，你还需要安装 CLI

```
npm install --save-dev webpack-cli
```

对于大多数项目，webpack 通过运行一个或多个 npm scripts，会在本地 node_modules 目录中查找安装的 webpack：

```
"scripts": {
    "start": "webpack --config webpack.config.js"
}
```


#### 二，全局安装

```
npm install --global webpack
```
