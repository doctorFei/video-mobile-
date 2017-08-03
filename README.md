# video-mobile
![im-js-logo](./doc/img/h5.jpg)

>使用Html+CSS+Javascript开发web前端，使用node.js开发web后台，完成的一套视频网站Demo 

项目主页 [Github-video-mobile](https://github.com/doctorFei/video-mobile)

## 写在前面
* 本次主要是开发一个移动端的视频展示、预览的H5，打开的第一个页面是《视频分栏目展示列表页面》，这里可以自己造一些假数据来模拟视频信息。  
* 当用户点击视频区域之后，需要在后台检查当前session是否登录，如果未登录，需要跳转到登录页面。  
* 用户提交登录信息之后，web后端在session中保存其登录信息，并返回前台。前端发现用户登录之后，跳转到《视频详情页面》，在《视频详情页面》中，用户可以查看视频信息，并观看视频（支持暂停、进度等）


## 实现效果


首页  |登录页| 详情页
:-:|:-:|:-:
![首页](./doc/img/1.png) | ![登录页](./doc/img/2.png)| ![详情页](./doc/img/3.png)

## 运行项目

**安装依赖**  
```shell
npm install
```
**进入开发模式**
```shell
npm start
之后打开 localhost:3000 查看
```
