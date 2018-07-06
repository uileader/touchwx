<p align="center">

<img width="200" height="200" src="https://github.com/uileader/touchui/blob/master/images/about_logo.png" />

</p>

<h1 align="center">Touch WX</h1>



####  Touch WX部分组件

<img src="https://github.com/uileader/touchui/blob/master/img/2.png" />





## 介绍

Touch WX是一套完全免费的微信小程序开发框架，包含丰富的UI控件用于官方组件的补充。特点如下：

##### 1、组件扩充：

增加了30多种常用的组件用于官方组件的补充。

##### 2、功能扩充：

兼容阿里的iconfont图标库，海量矢量图标随意使用；补充了常用样式库、支持less语法、支持全局配置主题色等

##### 3、开发体验改善：

四文件方式改为单文件方式，通过VSCode编辑器+插件的方式开发，拥有web开发体验；

##### 4、小程序转为H5应用：

可以与H5开发框架Touch UI工程相互转换，发布成webApp。开发一套代码，拥有两套应用。

##### 这套框架的原理是：

将Touch WX工程中所写的代码进行编译，直接输出为微信小程序工程原始代码。扩充的30多种组件，完全是基于小程序官方的自定义组件机制实现（row&col除外）。

所以它支持小程序的全部语法，怎么开发小程序，就怎么开发Touch WX。

不过因为是单文件的开发方式，在文件的代码结构上稍有不同。请注意这一点。

这样好处在于：

##### 1、开发者迁移成本很小。

可以轻松的将已有的小程序移植为Touch WX工程，来使用它的扩展能力；

##### 2、便于排查错误。

当遇到问题时，开发者也可以随时查看输出的小程序原始代码来定位问题所在。不会搞不清楚到底是框架问题还是自己代码的问题；

##### 3、按需编译

由于小程序对体积有限制，在使用框架开发时，只有使用到的组件才会编译输出为小程序源码。没用到的不会输出。

##### 4、不会对框架产生依赖。

以后不想用了这套框架，可以直接对已经输出的小程序工程进行维护。

## 注意事项

如果已经之前已经使用过Touch WX，运行过基础工程，可以跳过1、2步骤，直接开始第3步。

1、在本地运行代码时，需要安装Touch WX插件。

2、全局安装touchui-wx-cli

```
npm install -g touchui-wx-cli
```

3、右键，将该项目识别为Touch WX工程。

4、右键，安装项目依赖。如果没有成功的安装项目依赖，会报如下错误。

 <img src="http://images.uileader.com/20180528/704ed529-b1d0-4e87-9e55-c26b72be3030.png" />



详情可以参考下面的Touch WX文档。

环境安装：“入门 >> 起步 >> 环境安装”

第一个程序：“入门 >> 起步 >> 第一个程序”

## 文档

<a href="http://www.wetouch.net/touchwx_doc">中文文档</a>

## Demo

 <img src="http://static.uileader.com/touchui/img/minapp.jpg" />



## 讨论组

加下面的小助手微信进交流群。

 <img src="http://www.touchui.io/img/weixin_frank.png" />



## 相关项目

<a href="https://github.com/uileader/touchui" >Touch UI</a>

Touch UI是一套高质量移动端UI框架。基于vue.js框架，我们精心打造了上百种的移动端UI组件，几乎囊括了开发移动应用的所有细节，真正实现拿来即用，像搭积木一样开发移动应用。
