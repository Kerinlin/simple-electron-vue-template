# electron-vue

## 更新vue3相关版本模板
1. [vue-next-electron-template](https://github.com/Kerinlin/vue-next-electron-template)
2. [vue-next-start-template](https://github.com/Kerinlin/vue3-start-template)
3. [vue-next-vite-template](https://github.com/Kerinlin/vue-next-vite-template)

全部换成pnpn,集成unocss，prettier,eslint,方便快速搭建学习环境


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
