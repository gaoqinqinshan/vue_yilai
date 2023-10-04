# vue_yilai 这是在创建vue项目需要引入的element依赖

## main.js里面引入
``` 
import ElementUI from 'element-ui'
import 'element-ui/lib/theme-chalk/index.css'
Vue.use(ElementUI)
```
## 配置淘宝镜像源
```
npm config set registry http://registry.npm.taobao.org/
```

## 查看当前的镜像源
```
npm get registry 
```
## 恢复官方的镜像源
```
npm config set registry https://registry.npmjs.org
```

## 清除npm缓存
```
npm cache clean --force
```
