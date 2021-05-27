# electron-vue


## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn electron:serve
```

### Compiles and minifies for production
```
yarn electron:build
```

### Feature
1. 升级electron版本，兼容mac m1；
2. 添加打包，自动更新相关配置;
3. 通过preload使渲染进程拥有使用node模块的能力；
