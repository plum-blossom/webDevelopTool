---
title: 前端开发在线工具
date: 2019-03-25 15:58:40
tags: 
- 
categories: 
- 
---


<!-- more -->
# 前端开发工具总结

## 在线工具
* [程序员在线工具](http://www.ofmonkey.com/)
> 加密解密、字符转换、代码格式化、正则表达式、单位换算、二维码生成、条形码生成		

* [字符转线条字-在线工具](http://www.bejson.com/convert/str2img/)  
* [Iconfont-阿里巴巴矢量图标库](https://www.iconfont.cn/)	
* [fontawesome图标在线查询](http://www.bejson.com/ui/fontawesome/)	
* [fontawesome矢量图标库](https://fontawesome.com/icons?from=io)	
* [fontawesome中文文档](http://www.fontawesome.com.cn/)	
* [在线代码编译器](http://www.bejson.com/pages/cooleditor/)	
* [在线正则表达式](http://tool.chinaz.com/tools/regexgenerate/)	
* [在线生成指定大小、格式(支持webp)的图片](http://www.bejson.com/ui/imagehandler/)	
* [在线图片格式转换](http://www.bejson.com/convert/picture_format/)	
* [Html/MarkDown互转工具](http://www.bejson.com/convert/html2markdown/)	
* [在线gif制作工具](http://www.matools.com/gif)
* [Web酷炫特效在线地址](http://gnipbao.github.io/h5-test/menu.html);
## CSS在线工具
[阴影](https://testdrive-archive.azurewebsites.net/Graphics/hands-on-css3/hands-on_box-shadow.htm)	
[圆角](https://testdrive-archive.azurewebsites.net/Graphics/hands-on-css3/hands-on_box-shadow.htm)	
[文本阴影](https://testdrive-archive.azurewebsites.net/Graphics/hands-on-css3/hands-on_box-shadow.htm)	

## 辅助工具
[汉字拼音转换](https://www.npmjs.com/package/pinyin)	
[Bootstrap可视化布局系统](http://www.bootcss.com/p/layoutit/)	
[常用的HTML和CSS content属性特殊字符归纳](https://blog.csdn.net/zx562602419/article/details/81020342)	
[验证码插件Verify](https://veui.net/)  
> 开源，免费的验证码插件，自适应兼容移动端！			

[swiper](https://2.swiper.com.cn/)		
> Swiper常用于移动端网站的内容触摸滑动
> ![图片](swiper.png)

[基于HTML5 canvas圆形倒计时器jQuery插件效果演示](http://www.htmleaf.com/Demo/201502111367.html)
> 这是一款基于html5 canvas的圆形倒计时器jQuery插件。它可以使你非常轻松的创建圆形的倒计时器。该jQuery倒计时器插件有12种themes，它们基于 HTML5 canvas 来渲染各种圆环。
> ![图片](time.png)

[html5视频背景插件vidbacking](http://demo.htmleaf.com/1707/201707251501/index.html)
> vidbacking是一款响应式的，跨平台的html5视频背景插件。该视频背景插件允许你在页面中的某个div后整个页面中使用HTML5视频作为背景
> ![图片](vidbacking.png)

[17种基于mo.js制作的炫酷图标动画特效](http://www.htmleaf.com/html5/SVG/201602243142.html)
> 这是一款基于mo.js制作的一组炫酷图标动画特效。这组图标动画共有17种效果，它们使用font-awesome作为图标，采用SVG技术，在用户点击图标时产生各种炫酷的图标动画特效
> ![图片](mo.png)

[jTopo](http://www.jtopo.com/index.html)
> 是一款完全基于HTML5 Canvas的关系、拓扑图形化界面开发工具包。
> jTopo关注于数据的图形展示，它是面向开发人员的，需要进行二次开发。
> 使用jTopo很简单，可以快速创建一些关系图、拓扑等相关图形化的展示。只要您的数据之间存在有关联关系，都可以使用jTopo来进行人性化、图形化的展示。
> jTopo的目标：1.简单好用 2.灵活扩展 3.轻松开发出类似Visio、在线脑图、UML建模等类似工具 4.为大数据可视化提供解决方案  
![图片描述文字](jTopo_demo_img.png)


## 缓存	
[storage](https://github.com/ustbhuangyi/storage)	

## JavaScript
[Babel](https://babeljs.io/docs/en/)	
>Babel是一个工具链，主要用于将ECMAScript 2015+代码转换为当前和旧版浏览器或环境中的向后兼容版本的JavaScript		

## 第三方库
### jQuery左右箭头和鼠标控制的板块滚动
[demo](http://www.jq22.com/demo/jQuery-hk-150407214616/)
![图片描述文字](leftrightMove.png)

### jQuery放大镜插件  		
[demo1](http://www.jq22.com/demo/demo2jQzoom-141021091548/)
		
![图片描述文字](fangdajing.png)
  		
[demo2](http://www.jq22.com/demo/jQuery-Zoom20160322/)
![图片描述文字](fangdajing2.png)

[demo3](http://www.jq22.com/demo/jQueryJpg201708110048/)
![图片描述文字](fangdajing3.png)	

### 懒加载插件
[参考链接](https://www.npmjs.com/package/lazy-load-img)
#### 使用方法
```
var lazyLoadImg = new LazyLoadImg({
	el: ul,    // dom元素下的图片
	mode: 'diy',    // 模式: 默认/自定义
	time: 300,    // 多长时间重新监听一次
	complete: true,    // 完成后自己销毁程序
	position: {    // 只要其中一个位置符合条件，都会触发加载机制
			top: 0,    // 元素距离顶部
			left: 0,    // 元素距离右边
			right: 0,    // 元素距离下面
			bottom: 0    // 元素距离左边
	},
	diy: { //设置图片剪切规则，diy模式时才有效果
			backgroundSize: 'cover',
			backgroundRepeat: 'no-repeat',
			backgroundPosition: 'center center'
	},
	before: function() {

	},
	success: function(el) {
			el.classList.add('success');
	},
	error: function(el) {
			el.src = './images/error.png';
	}
});
```
#### 实例参考（lazy-load-img文件夹）
### 红包雨特效		
[demo](http://www.jq22.com/demo/jqueryhby201811150953/)		
![图片描述文字](hongbao1.png)
![图片描述文字](hongbao.png)
### 图片放大插件		
[elevateZoom中文文档](https://www.myfreax.com/elevatezoom-image-zoom/)  
[demo](https://demo.demohuo.top/jquery/5/521/demo/)
![图片描述文字](imgsuofang.png)

## 日期处理库
### JavaScript 日期处理类库
[momentjs](http://momentjs.cn/)		
![图片](momentjs.png)		

## 可视化工具		
#### ECharts，一个使用 JavaScript 实现的开源可视化库，可以流畅的运行在 PC 和移动设备上，兼容当前绝大部分浏览器（IE8/9/10/11，Chrome，Firefox，Safari等），底层依赖轻量级的矢量图形库 ZRender，提供直观，交互丰富，可高度个性化定制的数据可视化图表。
[echarts](https://www.echartsjs.com/index.html)
## 兼容
### IE6-8不支持CSS3 Media Queries解决：https://www.bootcdn.cn/respond.js/
### IE9以下不支持h5解决：
``` 
<!--[if lt IE 9]>    //判断当前浏览器的版本是否小于IE 9
<script src="https://oss.maxcdn.com/libs/html5shiv/3.7.0/html5shiv.js"></script>
```

## 其他
### 前端开发工具辅助总卷：https://www.jianshu.com/p/6e635191205a
### Markdown 语法整理大集合2017 - 简书：https://www.jianshu.com/p/b03a8d7b1719


## 图标库
[iconmoon](https://icomoon.io/app/#/select)	
这是一个图标库，可以将.svg文件商城字体图标并应用		
下面是制作字体的步骤：	
![图片](iconmoon1.png)
![图片](iconmoon2.png)
![图片](iconmoon3.png)	
将下载的包解压，将fonts文件放到你的项目中
![图片](iconmoon4.png)

## Vue开发相关工具和第三方库
### Axios	
[npm安装及使用](https://www.kancloud.cn/yunye/axios/234845)	
#### 使用方法与步骤	
1.npm install axios	
	
2.执行GET请求
		
```
// 为给定 ID 的 user 创建请求
axios.get('/user?ID=12345')
  .then(function (response) {
    console.log(response);
  })
  .catch(function (error) {
    console.log(error);
  });

// 可选地，上面的请求可以这样做
axios.get('/user', {
    params: {
      ID: 12345
    }
  })
  .then(function (response) {
    console.log(response);
  })
  .catch(function (error) {
    console.log(error);
  });
```

3. 执行POST请求

```
axios.post('/user', {
    firstName: 'Fred',
    lastName: 'Flintstone'
  })
  .then(function (response) {
    console.log(response);
  })
  .catch(function (error) {
    console.log(error);
  });
```

4.执行多个并发请求	

```
function getUserAccount() {
  return axios.get('/user/12345');
}

function getUserPermissions() {
  return axios.get('/user/12345/permissions');
}

axios.all([getUserAccount(), getUserPermissions()])
  .then(axios.spread(function (acct, perms) {
    // 两个请求现在都执行完成
  }));
```
### better-scroll 
[参考链接](https://github.com/ustbhuangyi/better-scroll/blob/master/README_zh-CN.md)
##### better-scroll 是一款重点解决移动端（现已支持 PC 端）各种滚动场景需求的插件。它的核心是借鉴的 iscroll 的实现，它的 API 设计基本兼容 iscroll，在 iscroll 的基础上又扩展了一些 feature 以及做了一些性能优化
#### 使用步骤
* npm install better-scroll
* import BScroll from 'better-scroll'		
```
import BScroll from 'better-scroll'
let wrapper = document.querySelector('.wrapper')
let scroll = new BScroll(wrapper)
```

### Vuex	
### 使用步骤		
[vuex](https://vuex.vuejs.org/zh/guide/)
## PS使用
### 快捷键
> Ctrl + h 显示/隐藏参考线      
> Alt + 鼠标 缩放     
> 空格 + 鼠标 移动        
> 新建图形文件【Ctrl】+【N】     
> 新建图层【Ctrl】+【Shift】+【N】      
> 反向选择 【Ctrl】+【Shift】+【I】     
> 还原两步以上操作 【Ctrl】+【Alt】+【Z】     
> 剪切选取的图像或路径 【Ctrl】+【X】或【F2】      
> 从对话框新建一个图层 【Ctrl】+【Shift】+【N】     
> 以默认选项建立一个新的图层 【Ctrl】+【Alt】+【Shift】+【N】      
> 通过拷贝建立一个图层 【Ctrl】+【J】     
> 通过剪切建立一个图层 【Ctrl】+【Shift】+【J】     
> ctrl+d-取消选定区域     
> ctrl+w-关闭文件     
> ctrl+Q-退出ps 

## HBuilder使用
### 快捷键
> ctrl+shift+d 插入选区或当前行		      
> ctrl+r 运行		   
> ctrl+alt+e,alt+f3 选择所有相同词		  
> ctrl+enter 直接从当前行末尾回车后跳转到下一行	  	
> Ctrl + Shift + Enter        将光标定位在上一行		  
> Ctrl + F4                   关闭		  
> Ctrl + Shift + F4           全部关闭		  
> Ctrl + H                    全局搜索		  
> Ctrl + T                    查找资源文件		  
> Ctrl + D										删除当前行		   
## 前端面试准备
### 参考链接
[前端面试知识点目录整理](https://mp.weixin.qq.com/s/8rbp-f1j8kz8XDxpAiSLvA?tdsourcetag=s_pcqq_aiomsg)

## CMD 使用
### 生成项目树
#### 在要生成的文件夹中 shift+鼠标右键打开cmd，输入tree /f，然后复制项目树就行
## 游戏开发
### 工具
![图片](gamePro1.png)		
![图片](gamePro2.png)		
### 文档
[白鹭开发者中心](http://developer.egret.com/cn/)	

## 游戏开发之Cocos Creator
### 记录
1. 安装Cocos Creator，[官网下载地址](https://www.cocos.com/creator)，默认安装在C盘就行，其他位置会报错。		
2. [开发文档](https://docs.cocos.com/creator/manual/zh/)
3. 创建UI节点之Layout布局，实现子节点排列
![图片](layout排列子节点.png)
4. UI组件ScrollView

 
