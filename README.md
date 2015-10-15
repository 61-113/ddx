# ddx

我写的这是简单的一个博客？
总之还有很多问题，我会继续完善，也会尝试多增加点功能，主要是前端react，学习嘛，就是得折腾

## 使用到的技术
- React.js
  - webpack
  - redux
  - react-router
- Node.js
  - koa
- Mongodb

## 怎样启动？
1. 依赖mongodb,所以您需要先安装mongodb，并且启动,建立一个数据库
2. 进入项目目录，执行```bash npm install  // 也可以使用cnpm install 来安装 ```
3. 😎进入下一步

### 开发模式
- 服务端自动重启
- 前端监控项目文件，有任何改动则会自动重启，无需浏览器自动F5。

***

服务端：
```bash
npm run server-watch
```

前端：
```bash
npm run client-watch
```

### 发布模式
- 服务端使用pm2 or 其他等等启动 (我这里仅仅是很简单的启动而已)
- 前端各种编译打包压缩代码。

***

服务端：
```bash
npm run server-start
```
前端：
```bash
npm run client-build
```

新建两个命令行窗口，第一个窗口执行
```bash
npm run client-watch
```
第二个窗口执行
```bash
npm run server-watch
```
或者你也可以在一个窗口上执行
```bash
npm run server-watch & npm run client-watch
```

最后，以上开发都在Mac上进行。 windows能try就try吧😂......
