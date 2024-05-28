# react
## 安装
### 老式脚手架
#### 全局安装
```
npm install -g create-react-app
```
#### 创建项目my-app自动创建目录
```
create-react-app my-app
```
*不能包含大写字母，执行该命令，就相当于webpack的基本环境都搭建完毕

### next
```
npx create-next-app@latest
```
## 路由
### react-router-dom
网址:
1. [官方](https://react-guide.github.io/react-router-cn/docs/Introduction.html)
2. [NPM](https://www.npmjs.com/package/react-router-dom)
#### 安装
```
npm i react-router-dom
```
#### 配置
##### App
```
import * as React from "react";
import { BrowserRouter } from "react-router-dom";

function App() {
  return <BrowserRouter>
    {/* The rest of your app goes here */}
  </BrowserRouter>
}

export default App;
);
```
## Markdown
网址:[官方](https://markdown.com.cn/)
