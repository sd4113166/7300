# 教程  
  教程地址： http://www.runoob.com/html/html-tutorial.html
# HTML 简介
## HTML 前世今生
    由来
    万维网上的一个超媒体文档称之为一个页面
    （外语：page） 。
    作为一个组织或者个人在万维网上
    放置开始点的页面称为 主页
    （外语：Homepage）或首页，
    主页中通常包括有指向
    其他相关页面或其他节点的指针（超级链接），
    所谓超级链 接，
    就是一种统一资源定位器
    （Uniform Resource  Locator，
    外语缩写：URL）指针，
    通过激活（点击）它，
    可使浏览器方便地获取新的网页。
    这也是HTML获得广泛应用 
    的最重要的原因之一。
    在逻辑上将视为一个整体的一系列页 
    面的有机集合称为网站（Website或Site）。
    超级文本标记 语言（英文缩写：HTML）
    是为“网页创建和其它可在网页浏 
    览器中看到的信息”设计的一种标记语言。
    网页的本质就是超级文本标记语言，
    通过结合使用其他的 Web技术
    （如：脚本语言、公共网关接口、组件等），
    可以 创造出功能强大的网页。
    因而，超级文本标记语言是万维网 
    （Web）编程的基础，
    也就是说万维网是建立在超文本基础
    之上的。
    超级文本标记语言之所以称为超文本标记语言，
    是 因为文本中包含了所谓“超级链接”点。
    
[参考地址] (https://baike.baidu.com/item/HTML/97049? fr=aladdin)
## HTML 实例
    <!DOCTYPE html>
    <html>
    <head>
       <meta charset="utf-8">
        <title>菜鸟教程(runoob.com)</title>
    </head>
    <body>
 
      <h1>我的第一个标题</h1>
 
      <p>我的第一个段落。</p>
 
    </body>
    </html>
## 实例解析
    <!DOCTYPE html> 声明为 HTML5 文档
    <html> 元素是 HTML 页面的根元素
    <head> 元素包含了文档的元（meta）数据
    <title> 元素描述了文档的标题
    <body> 元素包含了可见的页面内容
    <h1> 元素定义一个大标题
    <p> 元素定义一个段落
## 什么是HTML?
    HTML 是用来描述网页的一种语言。
    HTML 指的是超文本标记语言: HyperText Markup Language
    HTML 不是一种编程语言，而是一种标记语言
    标记语言是一套标记标签 (markup tag)
    HTML 使用标记标签来描述网页
    HTML 文档包含了HTML 标签及文本内容
    HTML文档也叫做 web 页面
## HTML 标签
    HTML 标记标签通常被称为 HTML 标签 (HTML tag)。
    HTML 标签是由尖括号包围的关键词，比如 <html>
    HTML 标签通常是成对出现的，比如 <b> 和 </b>
    标签对中的第一个标签是开始标签，第二个标签是结束标签
    开始和结束标签也被称为开放标签和闭合标签
    <标签>内容</标签>
## HTML 元素
    "HTML 标签" 和 "HTML 元素" 
    通常都是描述同样的意思.
    但是严格来讲, 一个 HTML 
    元素包含了开始标签与结束标签，如下实例:
    HTML 元素:  <p>这是一个段落。</p>
## Web 浏览器
    Web浏览器（如谷歌浏览器，
    Internet Explorer，Firefox，Safari）是用于读取HTML文件，
    并将其作为网页显示。
    浏览器并不是直接显示的HTML标签，
    但可以使用标签来决定如何展现HTML
    页面的内容给用户：

![image](1-1WebBrowse.jpg)

## HTML 网页结构
   下面是一个可视化的HTML页面结构：
![image](1-1structrue.jpg)   
## HTML版本
   从初期的网络诞生后，已经出现了许多HTML版本:
![image](1-1HtmlVersion.jpg)   
## <!DOCTYPE> 声明
   <!DOCTYPE>声明有助于浏览器中正确显示网页。
   网络上有很多不同的文件，如果能够正确声明HTML的版本，浏览器就能正确显示网页内容。
   doctype 声明是不区分大小写的，以下方式均可： 
   <!DOCTYPE html> 
   <!DOCTYPE HTML> 
   <!doctype html> 
   <!Doctype Html>
# 通用声明

![image](1-1html5.jpg)   
   查看完整网页声明类型[DOCTYPE 参考手册](http://www.runoob.com/tags/tag-doctype.html) 。

# 中文编码

   目前在大部分浏览器中，直接输出中文会出现中文乱码的情况，这时候我们就需要在头部将字符声明为 UTF-8。
   <!DOCTYPE html>
    <html>
    <head>
       <meta charset="utf-8">
        <title>菜鸟教程(runoob.com)</title>
    </head>
    <body>
 
      <h1>我的第一个标题</h1>
 
      <p>我的第一个段落。</p>
 
    </body>
    </html>

#  介绍主流HTML 编辑器
## 可以使用专业的 HTML 编辑器来编辑 HTML，菜鸟教程为大家推荐几款常用的编辑器：
   Visual Studio Code:  https://code.visualstudio.com/?wt.mc_id=vscom_downloads

   Sublime Text：http://www.sublimetext.com/

   Notepad++：https://notepad-plus-plus.org/

   HBuilder：http://www.dcloud.io/kkkkkkk
   
## 编辑器的安装
   visual studio code 安装


## 让学员熟悉编辑器
   常用的一些快捷键
   Ctrl+N  Ctrl+S Ctrl+z  ctrl+x  ctrl+a ctrl+c  ctrl+x
   ctrl+tab ctrl+h  ctrl+F

   关于visual studio code 详细操作 会在1.4.1编辑这节课中介绍
   更多参考  http://blog.csdn.net/crper/article/details/54099319
   

## 让学员了解 Emment
快捷皱键参考网址https://www.w3cplus.com/tools/emmet-cheat-sheet.html

关于emment 详细操作 会在1.4.2编辑这节课中介绍

## 让学员编写第一个程序
让学员自己编程人生第一个程序hello world!
 
## 编写第一个程序步骤
   
    打开编辑器visual studio code
 
    新建文件  

    文件保存

    写代码
    <!DOCTYPE html>
      <html>
       <head>
           <meta charset="utf-8">
           <title>菜鸟教程(runoob.com)</title>
        </head>
        <body>
            <h1>我的第一个标题</h1>
            <p>我的第一个段落。</p>
        </body>
        </html>

## 调试
    
    在浏览器中查看网页元素。
    查看元素操作的步骤
    鼠标右键查看
   




## 作业
    用网页的形式介绍自己，包括姓名 、年龄、
    爱好、性别、等个 人信息（可以写假信息）

    要求 使用以下标签 
    <p> <hr> <strong> <h1>至<h6> 
    <i>  <b>  <sub>   <sup> 多个段落展示
    并且用注释来标注这个段落是什么内容 
    在 <title></title>里填上自己的名字
    用加长文本标签<blockquote>引用你最喜爱圣经上一句话 

    加分项 设置自己喜爱的颜色为字体的前景色
    加分项 在网页里显示自己的照片（也可以用其它图片代替)
    加分项 在网页里跳转到自己的 www.baidu.com
    加分项 在网页里播放自己喜爱的 赞美

    

    练习 ctrl+n  ctrl+Z   ctrl+y  ctrl+s 
         ctrl+a  ctrl+x  ctrl+f  ctrl+H
         ctrl+x  ctrl+c ctrl+v  ctrl+tab
         alt+v  alt+f  alt+e
