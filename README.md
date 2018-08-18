
## HTML5-Player


### 一、简介
该项目是基于 vue 全家桶仿写的一个旅游app项目，技术栈采用：vue + vuex + + vue-router +axios + es6 + stylus 

1、项目依赖基本核心版本：
* "axios": "^0.18.0",
* "babel-polyfill": "^6.26.0",
* "better-scroll": "^1.12.5",
* "fastclick": "^1.0.6",
* "stylus": "^0.54.5",
* "stylus-loader": "^3.0.2",
* "vue": "^2.5.2",
* "vue-awesome-swiper": "^2.6.7",
* "vue-router": "^3.0.1",
* "vuex": "^3.0.1"

2、该app基本功能：
* 首页开发
  *Header制作
  *Iconfont的引入
  *首页轮播
  *图标区域实现
  *热销推荐与周末游组件
  *使用axios获取接口数据
  *首页父子组件间数据的传递
* 城市选择页面开发
  *路由配置
  *搜索框布局
  *Better-scroll的使用和字母表布局
  *兄弟组建间的传值
  *列表性能优化
  *搜索逻辑实现
  *Vuex实现数据共享
  *LocalStorage实现页面数据持久存储
  *使用keep-alive优化路由页面性能
* 详情页面开发
  *动态路由配置及banner布局
  *公用画廊组件拆分
  *渐隐渐显的header效果实现
  *递归组件实现详情列表
  *画廊动画效果封装

3、项目图片预览：

![首页](/pic.png)

### 二、项目结构

```javascript
│  App.vue
│  main.js
│
├─assets
│  └─styles
│      │  border.css
│      │  iconfont.css
│      │  mixins.styl
│      │  reset.css
│      │  varibles.styl
│      │
│      └─iconfont
│              iconfont.eot
│              iconfont.svg
│              iconfont.ttf
│              iconfont.woff
│
├─common
│  ├─fade
│  │      FadeAnimation.vue
│  │
│  └─gallary
│          Gallary.vue
│
├─pages
│  ├─city
│  │  │  City.vue
│  │  │
│  │  └─components
│  │          Alphabet.vue
│  │          Header.vue
│  │          List.vue
│  │          Search.vue
│  │
│  ├─detail
│  │  │  Detail.vue
│  │  │
│  │  └─components
│  │          Banner.vue
│  │          Header.vue
│  │          List.vue
│  │
│  └─home
│      │  Home.vue
│      │
│      └─components
│              Header.vue
│              Icons.vue
│              Recommend.vue
│              Swiper.vue
│              Weekend.vue
│
├─router
│      index.js
│
└─store
        index.js
        mutations.js
        state.js
```
### 三、如何执行

####  1、将项目克隆到本地，cd 到 HTML5-Player
```javascript
git clone 
cd 
```
#### 2、安装依赖
```javascript
npm install or yarn install
```
#### 3、执行
```javascript
npm run dev
// npm run build(打包)
```
#### 4、打开浏览器浏览 [http://localhost:8080/](http://localhost:8080/)，强烈建议使用 Chrome、Firefox 浏览器浏览。

