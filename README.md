## HTML5-Player


### 一、简介
该项目是基于 zepto 开发的一个音乐播放器，技术栈采用：gulp + zepto + html5 + es6 + css3

1、项目依赖基本核心版本：
* gulp: "^3.9.1",
* gulp-concat: "^2.6.1",
* gulp-connect: "^5.5.0",
* gulp-deporder: "^1.1.0"
* gulp-htmlclean: "^2.7.20",
* gulp-imagemin: "^4.1.0",
* gulp-less: "^3.5.5",
* gulp-postcss: "^7.0.1",
* gulp-strip-debug: "^3.0.0",
* gulp-uglify: "^3.0.0",
* jquery: "^3.3.1"

2、该音乐播放器基本功能：
* 音乐的播放、暂停、上一首、下一首；
* 控制进度条位置；
* 背景图片高斯模糊；
* 喜欢音乐加入收藏列表；

3、项目动图预览：

![首页](/pic.gif)

### 二、项目结构

```javascript
├─css
│      index.css
│
├─html
│      index.html
│
├─images
│      icon-close.png
│      icon-like-solid.png
│      icon-like.png
│      icon-list.png
│      icon-next.png
│      icon-pause.png
│      icon-play.png
│      icon-playlist.png
│      icon-prev.png
│
├─js
│      audioManager.js
│      controlManager.js
│      controlMananger.js
│      gaussBlur.js
│      index.js
│      playlist.js
│      processor.js
│      render.js
│      zepto.min.js
│
└─mock
        data.json
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
npm start or yarn start
// npm run build(打包)
```
#### 4、打开浏览器浏览 [http://localhost:8080/](http://localhost:8080/)，强烈建议使用 Chrome、Firefox 浏览器浏览。

