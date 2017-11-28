# 3.HTML 复杂元素
## 3.1 HTML 表格

    掌握以下标签元素<table> <th> <tr> <td> <caption>
     
    <colgroup> <col> <thead> <tbody> <tfoot>

[教程地址](http://www.runoob.com/html/html-tables.html)

## 3.2HTML 列表

    列表分类：有序、无序、自定义列表。

    无序列表：是一个项目的列表，此列项目使用粗体圆点（典型小 黑圆圈）进行标记。无序列表使用 <ul> 标签，每个列表项于  <li> 标签。

    有序列表：也是一列项目，列表项目使用数字进行标记。 有序表 始于 <ol> 标签，每个列表项始于 <li> 标签。列表项项用数字 来标记。 

    自定义列表：不仅仅是一列项目，而是项目及其注释的组合。定 义列表以 <dl> 标签开始。
    每个自定义列表项以 <dt> 始。每个 自定义列表项的定义以
    <dd> 开始。

    提示: 列表项内部可以使用段落、换行符、图片、链接以及其列 表等等。
 
    撑握以下标签元素使用方法:
    <ol> 定义有序列表
    <ul> 定义无序列表
    <li> 定义列表项
    <dl> 定义列表
    <dt> 自定义列表项目
    <dd> 定义自定列表项的描述
[教程地址](http://www.runoob.com/html/html-lists.html)


## 3.3 div元素和span元素
    
    HTML <div> 元素是块级元素，它可用于组合其他 HTML 元素的容器。<div> 元素没有特定的含义。除此之外，由于它属于块级元素，浏览器会在其前后显示折行。
    如果与 CSS 一同使用，<div> 元素可用于对大的内容块设置样式属性。<div> 元素的另一个常见的用途是文档布局。它取代了使用表格定义布局的老式方法。使用 <table> 元素进行文档布局不是表格的正确用法。<table> 元素的作用是显示表格化的数据。

    HTML <span> 元素HTML <span> 元素是内联元素，可用作文本的容器<span> 元素也没有特定的含义。
    当与 CSS 一同使用时，<span> 元素可用于为部分文本设置样式属性。

[教程地址](http://www.runoob.com/html/html-blocks.html)   
## 3.4 布局
    网站布局
    大多数网站会把内容安排到多个列中（就像杂志或报纸那样）。大多    数网站可以使用 <div> 或者 <table>元素来创建多列。CSS 用于对    元素进行定位，或者为页面创建背景以及色彩丰富的外观。
[教程](http://www.runoob.com/html/html-layouts.html)

## 3.5 HTML 表单和输入

    表单是一个包含表单元素的区域。表单元素是允许用户在表单中输入内容,比如：文本域(textarea)、下拉列表、单选框(radio-buttons)、复选框(checkboxes)等等。表单使用表单标签 <form> 来设置:
[教程](http://www.runoob.com/html/html-forms.html)

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
[教程](http://www.runoob.com/html/html-forms.html)

## 3.6 iframe HTML 框架
    框架:通过使用框架，你可以在同一个浏览器窗口中显示不止一个页面。
##  设置高度与宽度
    height 和 width 属性用来定义iframe标签
    的高度与宽度。
    属性默认以像素为单位, 但是你可以指
    定其按比例显示 (如："80%")。
##  Iframe - 移除边框
    frameborder 属性用于定义iframe表示是否显示边框。
    设置属性值为 "0" 移除iframe的边框
    使用iframe来显示目标链接页面
    iframe可以显示一个目标链接的页面
    目标链接的属性必须使用iframe的属性
[教程](http://www.runoob.com/html/html-iframes.html)
## 3.7 HTML 颜色
    HTML 颜色由红色、绿色、蓝色混合而成。
[教程](http://www.runoob.com/html/html-colors.html)
##  颜色值
    HTML 颜色由一个十六进制符号来定义，
    这个符号由红色、绿色和蓝色的值组成（RGB）。
    每种颜色的最小值是0（十六进制：#00）。
    最大值是255（十六进制：#FF）。
    这个表格给出了由三种颜色混合而成的具体效果：
    颜色
[教程](http://www.runoob.com/html/html-colors.html)
##  1600万种不同颜色
    三种颜色 红，绿，蓝的组合从0到255，
    一共有1600万种不同颜色(256 x 256 x 256)。
    在下面的颜色表中你会看到不同的结果，
    从0到255的红色，同时设置绿色和蓝色的值为0,
    随着红色的值变化，不同的值都显示了不同的颜色
[教程](http://www.runoob.com/html/html-colors.html)
##  Web安全色?
    数年以前，当大多数计算机仅支持 256 种颜色的时候，一系列   216 种 Web 安全色作为 Web 标准被建议使用。其中的原因是， 微软和 Mac 操作系统使用了 40 种不同的保留的固定系统颜色   (双方大约各使用 20 种)。我们不确定如今这么做的意义有多大，
    因为越来越多的计算机有能力处理数百万种颜色，不过做选择还是你自己。最初，216 跨平台 web 安全色被用来确保：当计算机使用 256色调色板时，所有的计算机能够正确地显示所有的颜色。
[教程](http://www.runoob.com/html/html-colors.html)
## 3.8 HTML 字符实体
    HTML 中的预留字符必须被替换为字符实体。
    一些在键盘上找不到的字符也可以使用字符实体来替换。
## 撑握常用字符实体
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
[教程](http://www.runoob.com/html/html-entities.html)
 
## 3.9 作业 
    制作浑河堡教会小组报告表