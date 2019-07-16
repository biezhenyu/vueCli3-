# vue-template

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### vue的一套模板

#### layout组件 
为一个中间件存在，提供嵌套路由使用，并无其他功能

#### filter提供全局过滤器
需要配置的过滤器在filter下面配置, 引用已在main.js里面配置

#### util提供全局的工具方法
需要配置的工具函数在util下面配置

#### store vuex的配置


#### 打包
已在package.json里面配置本地，测试，预发布，正式等环境
.env则是对环境变量的配置

### 已经将vue.config.js文件引入

### api 文件主要对api进行了一层封装
这样不同的模块可以管理不同的api

### layout组件用来提供嵌套路由


