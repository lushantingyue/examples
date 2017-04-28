阅读笔记
========================

## 此项目基于 koa 1.0版本

#### 功能
```
  演示了处理404错误提示
```

#### 代码分析
```
    app.js:   
        this.accepts('html', 'json')
    test.js:
        单元测试
```
#### koa2 和 koa 1.x 的区别
      Koa2 应用了ES7的 Async/Await来替代 Koa1中的生成器函数generator与yield。
      
## 依赖的库
```
    "dependencies": {
    "koa": "^1.0.0",  // koa核心库
  }
  ```
