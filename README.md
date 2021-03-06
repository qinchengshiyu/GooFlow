# GooFlow

一个基于 Jquery/FontAwesome 的流程图/架构图画图插件 、展示控件。
fork 自https://github.com/huangjunsen/GooFlow 进行了一定的优化和调整。

### 版本
V1.0.0.1 

### 更新日志
* 2018-09-19:  
>>修改 ：修复了展示模式标线bug  
* 2018-09-13 (V1.0->V1.0.0.1)  
    修复:标线的时候线不能标记bug  
    优化:添加了标线颜色参数,使得标线的时候不仅仅是红色。  
    >>添加了展示模式配置 showmodel  
    >>添加了背景取消参数、工作区边框取消参数  
   
    

### 依赖
* jquery1.11+  
* fontawesome4.4.0+  

### 浏览器支持
* IE9+  
* Firefox (latest)  
* Safari (latest)  
* Chrome (latest)  
* Opera (latest)  
* IE9 不支持CSS变形和动画，此插件的功能都能用，不过，拥有较差的用户体验。  

### 1. 示例
* 编辑模式
![](https://github.com/QCSYSTUDIO/GooFlow/blob/master/SnapShot/01_Example.jpg)  
* 展示模式
![](https://github.com/QCSYSTUDIO/GooFlow/blob/master/SnapShot/showModel.jpg)  
### 2. 使用方法：
2.1. 添加CSS及JS文件  
```html
<link rel="stylesheet" href="dist/GooFlow.min.css">
<link rel="stylesheet" href="fontawesome/css/font-awesome.min.css">
<script src="dist/jquery.min.js"></script>
<script src="dist/GooFlow.min.js"></script>
```

2.2. 书写容器 Dom   
```html
<div id="demo1"></div> 
```

2.3. 激活/生成：  
```javascript
var demo1 = $('#demo1').createGooFlow(options);
```

  
### 3. 操作手册(API)：
如果无法打开网页，请下载项目查看demo.html 及api.html
* 查看API  
http://htmlpreview.github.io/?https://github.com/QCSYSTUDIO/GooFlow/blob/master/api.html
* 查看demo  
http://htmlpreview.github.io/?https://github.com/QCSYSTUDIO/GooFlow/blob/master/demo.html

  
