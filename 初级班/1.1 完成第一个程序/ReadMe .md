# 教程  
  教程地址： http://www.runoob.com/html/html-tutorial.html
# HTML 简介
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

##  检查学员完成情况
    统计学员完成的情况 
    程序完成请在QQ群里打1
    由最先完成的学员 给大家讲解

## 布局
    网站布局
    大多数网站会把内容安排到多个列中
    （就像杂志或报纸那样）。
    大多数网站可以使用 <div> 或者 <table>
    元素来创建多列。
    CSS 用于对元素进行定位，
    或者为页面创建背景以及色彩丰富的外观。
## HTML 布局 - 有用的提示
    Tip: 使用 CSS 最大的好处是，如果把 CSS 
    代码存放到外部样式表中，那么站点会更易于维护。
    通过编辑单一的文件，就可以改变所有页面的布局。
    如需学习更多有关 CSS 的知识，
    请访问我们的CSS 教程。
    Tip: 由于创建高级的布局非常耗时，
    使用模板是一个快速的选项。
    通过搜索引擎可以找到很多免费的网站模板
    （您可以使用这些预先构建好的网站布局，并优化它们）。

## HTML 表单和输入
    HTML 表单
    表单是一个包含表单元素的区域。
    表单元素是允许用户在表单中输入内容,比如：
    文本域(textarea)、下拉列表、
    单选框(radio-buttons)、
    复选框(checkboxes)等等。
    表单使用表单标签 <form> 来设置:
## 要求熟练掌握以下标签元素
    <form>	定义供用户输入的表单
    <input>	定义输入域
    <textarea>	定义文本域 (一个多行的输入控件)
    <label>	定义了 <input> 元素的标签，
    一般为输入标题
    <fieldset>	定义了一组相关的表单元素，
    并使用外框包含起来
    <legend>	定义了 <fieldset> 元素的标题
    <select>	定义了下拉选项列表
    <optgroup>	定义选项组
    <option>	定义下拉列表中的选项
    <button>	定义一个点击按钮
    <datalist>New	指定一个预先定义的输入控件选项列表
    <keygen>New	定义了表单的密钥对生成器字段
    <output>New	定义一个计算结果
## iframe HTML 框架
    通过使用框架，你可以在同一个浏览器窗口中显示不止一个页面。
##  Iframe - 设置高度与宽度
    height 和 width 属性用来定义iframe标签
    的高度与宽度。
    属性默认以像素为单位, 但是你可以指
    定其按比例显示 (如："80%")。
## Iframe - 移除边框
    frameborder 属性用于定义iframe表示是否显示边框。
    设置属性值为 "0" 移除iframe的边框:
## 使用iframe来显示目标链接页面
    iframe可以显示一个目标链接的页面
    目标链接的属性必须使用iframe的属性，如下实例:
##  HTML 颜色
    HTML 颜色由红色、绿色、蓝色混合而成。
##  颜色值
    HTML 颜色由一个十六进制符号来定义，
    这个符号由红色、绿色和蓝色的值组成（RGB）。
    每种颜色的最小值是0（十六进制：#00）。
    最大值是255（十六进制：#FF）。
    这个表格给出了由三种颜色混合而成的具体效果：
    颜色值
##  1600万种不同颜色
    三种颜色 红，绿，蓝的组合从0到255，
    一共有1600万种不同颜色(256 x 256 x 256)。
    在下面的颜色表中你会看到不同的结果，
    从0到255的红色，同时设置绿色和蓝色的值为0,
    随着红色的值变化，不同的值都显示了不同的颜色。
##  Web安全色?
    数年以前，当大多数计算机仅支持 256 种颜色的时候，
    一系列     216 种 Web 安全色作为 Web 
    标准被建议使用。其中的原因是，   
     微软和 Mac 操作系统使用了 
     40 种不同的保留的固定系统颜色    
    （双方大约各使用 20 种）。
    我们不确定如今这么做的意义有多大，
    因为越来越多的计算机有能   
    力处理数百万种颜色，不过做选择还是你自己。
    最初，216 跨平台 web 安全色被用来确保：
    当计算机使用 256     
    色调色板时，
    所有的计算机能够正确地显示所有的颜色。

##  HTML 字符实体
    HTML 中的预留字符必须被替换为字符实体。
    一些在键盘上找不到的字符也可以使用字符实体来替换。
##  撑握常用字符实体
    HTML字符实体
    	空格	&nbsp;	&#160;
        <	小于号	&lt;	&#60;
        >	大于号	&gt;	&#62;
        &	和号	&amp;	&#38;
        "	引号	&quot;	&#34;
        '	撇号 	&apos; (IE不支持)	&#39;
        ￠	分	&cent;	&#162;
        £	镑	&pound;	&#163;
        ¥	人民币/日元	&yen;	&#165;
        €	欧元	&euro;	&#8364;
        §	小节	&sect;	&#167;
        ©	版权	&copy;	&#169;
        ®	注册商标	&reg;	&#174;
        ™	商标	&trade;	&#8482;
        ×	乘号	&times;	&#215;
        ÷	除号	&divide;	&#247;
## HTML 统一资源定位器(Uniform Resource Locators)
    URL 是一个网页地址。
    URL可以由字母组成，如"runoob.com"，
    
    或互联网协议（IP）地址： 192.68.20.50。
    大多数人进入网站使用网站域名来访问，
    因为 名字比数    更容易记住    