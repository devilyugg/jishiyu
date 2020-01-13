# 前言

#### 为类似于当前比较火热的外卖相似的APP

#### 该项目大大小小80多个页面，涉及注册、登录、商品展示、购物车、下单等等，是一个完整的流程。

####  注：此项目为外包项目，我留了一份。

## 技术栈

##### vue2 + vue-cli + vuex + vue-router + axios + webpack + ES6 + less

##### ui 库
* https://github.com/youzan/vant
* http://www.muse-ui.org/#/index
* http://mint-ui.github.io/#!/zh-cn 
* https://material.io/icons/

## 说明

> 在使用前需要安装vue     npm install --global vue-cli

> 安装完以后需要安装依赖   npm install


# 部分截图

### 商铺列表页

<img src="https://github.com/Besmall/vue-mt/blob/master/src/components/splb.png" width="365" height="619"/> <img src="https://github.com/Besmall/vue-mt/blob/master/src/components/splb.gif" width="365" height="619"/>


### 商铺筛选页

<img src="https://github.com/Besmall/vue-mt/blob/master/src/components/spsx.png" width="365" height="619"/> <img src="https://github.com/Besmall/vue-mt/blob/master/src/components/spsx.gif" width="365" height="619"/>

### 餐饮列表

<img src="https://github.com/Besmall/vue-mt/blob/master/src/components/canyin.png" width="365" height="619"/>

# 项目布局
```
├── build                                       // webpack配置文件
├── config                                      // 项目打包路径
├── mt                                         // 上线项目文件，放在服务器即可正常访问
├── screenshots                                 // 项目截图
├── src                                         // 源码目录
|   ├── components                              // 组件
|   ├── config                                  // 基本配置
|   ├── router
│   └── router.js  
|   ├── store                                   // vuex的状态管理// 路由配置
|   └──
│   ├── App.vue                                 // 页面入口文件
│   ├── main.js                                 // 程序入口文件，加载各种公共组件
├── favicon.ico                                 // 图标
├── index.html                                  // 入口html文件
```

