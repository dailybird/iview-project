# iView-project

This project is build for Vue.js 2 + vue-router + webpack2 + iView 2, just install and run.

## Install
```bush
// install dependencies
npm install
```
## Run
### Development
```bush
// For the first time, run init to create index.html
npm run init
npm run dev
```
### Production(Build)
```bush
npm run build
```

### 改动
1. 修改了 .gitignore 文件；

### 注意
1. 并入后台框架时需要调整 router 和根目录路径；
2. 虚拟主机使用 `index_prod.html` 作为入口文件，`npm run dev` 使用 `index.html`；

