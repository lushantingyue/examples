阅读笔记
========================

## 此项目基于 koa 1.0版本

#### 功能
```
  演示了使用co-body解析库对 post请求体 进行解析
```

#### 代码分析
```
    app.js:   
        post请求体解析
```
#### koa2 和 koa 1.x 的区别
      Koa2 应用了ES7的 Async/Await来替代 Koa1中的生成器函数generator与yield。
      
## 依赖的库
```
    "dependencies": {
    "co-body": "^1.0.0",  // post请求体解析, 在 koa2中建议替换为 koa-bodyparser
    "koa": "^1.0.0",  // koa核心库
  }
  ```
