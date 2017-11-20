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
    "HTML 标签" 和 "HTML 元素" 通常都是描述同样的意思.
    但是严格来讲, 一个 HTML 元素包含了开始标签与结束标签，如下实例:
    HTML 元素:  <p>这是一个段落。</p>
## Web 浏览器
    Web浏览器（如谷歌浏览器，Internet Explorer，Firefox，Safari）是用于读取HTML文件，并将其作为网页显示。
    浏览器并不是直接显示的HTML标签，但可以使用标签来决定如何展现HTML页面的内容给用户：

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