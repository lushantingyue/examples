阅读笔记
========================

## 此项目基于 koa 1.0版本

#### 功能
```
  演示了 使用koa-basic-auth库对 请求添加 Basic Auth 认证
```

#### 代码分析
```
    app.js:   
        对请求做认证检查, 捕捉 401状态并相应异常
```
#### koa2 和 koa 1.x 的区别
      Koa2 应用了ES7的 Async/Await来替代 Koa1中的生成器函数generator与yield。
      
## 依赖的库
```
    "dependencies": {
    "koa-basic-auth": "^1.1.1",  // post请求体解析, 在 koa2中建议替换为 koa-bodyparser
    "koa": "^1.0.0",  // koa核心库
  }
  ```
