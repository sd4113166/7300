# 1.4.1编辑器快捷键

    编辑器与窗口管理
    
    同时打开多个窗口（查看多个项目）
    
    打开一个新窗口： Ctrl+Shift+N
    关闭窗口： Ctrl+Shift+W
    同时打开多个编辑器（查看多个文件）
    
    新建文件 Ctrl+N
    文件之间切换 Ctrl+Tab
    切出一个新的编辑器（最多3个）Ctrl+\，
    也可以按住Ctrl鼠标点    击Explorer里的文件名
    左中右3个编辑器的快捷键Ctrl+1 Ctrl+2 Ctrl+3
    3个编辑器之间循环切换 Ctrl+`
    编辑器换位置，Ctrl+k然后按Left或Right
    代码编辑
    
    格式调整
    
    代码行缩进Ctrl+[ Ctrl+]
    Ctrl+C Ctrl+V如果不选中，
    默认复制或剪切一整行
    代码格式化：Shift+Alt+F，
    或Ctrl+Shift+P后输入format  code
    上下移动一行： Alt+Up 或 Alt+Down
    向上向下复制一行： Shift+Alt+Up或Shift+Alt+Down
    在当前行下边插入一行Ctrl+Enter
    在当前行上方插入一行Ctrl+Shift+Enter
    光标相关
    
    移动到行首：Home
    移动到行尾：End
    移动到文件结尾：Ctrl+End
    移动到文件开头：Ctrl+Home
    移动到定义处：F12
    定义处缩略图：只看一眼而不跳转过去Alt+F12
    移动到后半个括号 Ctrl+Shift+]
    选择从光标到行尾Shift+End
    选择从行首到光标处Shift+Home
    删除光标右侧的所有字Ctrl+Delete
    Shrink/expand selection： 
    Shift+Alt+Left和Shift+Alt    +Right
    Multi-Cursor：可以连续选择多处
    ，然后一起修改，Alt+Click添  
      加cursor或者Ctrl+Alt+Down
     或 Ctrl+Alt+Up
    同时选中所有匹配的Ctrl+Shift+L
    Ctrl+D下一个匹配的也被选中
    (被我自定义成删除当前行了，见下    
    边Ctrl+Shift+K)
    回退上一个光标操作Ctrl+U
    重构代码
    
    找到所有的引用：Shift+F12
    同时修改本文件中所有匹配的：Ctrl+F12
    重命名：比如要修改一个方法名，
    可以选中后按F2，
    输入新的名    字，回车，
    会发现所有的文件都修改过了。
    跳转到下一个Error或Warning：
    当有多个错误时可以按F8逐个跳    转
    查看diff 在explorer里选择文件右键 
    Set file to compare， 
       然后需要对比的文件上右键选择Compare with 
           'file_name_you_chose'.
    查找替换
    
    查找 Ctrl+F
    查找替换 Ctrl+H
    整个文件夹中查找 Ctrl+Shift+F
    
    显示相关
    
    全屏：F11
    zoomIn/zoomOut：Ctrl + =/Ctrl + -
    侧边栏显/隐：Ctrl+B
    侧边栏4大功能显示：
    Show Explorer Ctrl+Shift+E
    Show SearchCtrl+Shift+F
    Show GitCtrl+Shift+G
    Show DebugCtrl+Shift+D
    Show OutputCtrl+Shift+U
    其他
    
    自动保存：File -> AutoSave ，
    或者Ctrl+Shift+P，输入     auto
  [教程](http://blog.csdn.net/u010019717/article/details/50443970)  

## Emment 快捷键
   
    Emmet-前端开发神器
    Emmet是一款编辑器插件，支持多种编辑器支持。
    在前端开发中，Emmet 使用缩写语法快速编写 HTML、
    CSS 以及实现其他的功能，极大的提高前端开发效率。

    下载地址http://emmet.io/download/

    缩写
    Emmet使用特殊的表达式Abbreviations，
    也就是缩写：这种特殊的表达式会被Emmet
    解析并转义成结构化的代码块。
    Emmet使用类似CSS选择器的语法来描述元素
    在DOM树节点的位置和属性。

例如

     #page>div.logo+ul#navigation>li*5>a{Item $}
     会被转义成

    <div id="page">
        <div class="logo"></div>
        <ul id="navigation">
            <li><a href="">Item 1</a></li>
            <li><a href="">Item 2</a></li>
            <li><a href="">Item 3</a></li>
            <li><a href="">Item 4</a></li>
            <li><a href="">Item 5</a></li>
        </ul>
    </div>

   HTML元素

    在Emmet中可以使用元素名例如 div 或
     p 生成HTML标签。
    Emmet   没有预设任何标签名，
    所以可以使用任何可用名称来 生成HTML标 
    签：div → <div></div> 
    或 foo →  <foo></foo>

 嵌套操作符

    嵌套操作用来生成元素的DOM树中的兄弟节点或子节点

child：>
    
    使用 > 生成元素子节点
    div>ul>li
    会被转义成

    <div>
        <ul>
            <li></li>
        </ul>
    </div>
Sibling: +

    使用 + 生成元素兄弟节点
    div+p+bq
    会被转义成
    
    <div></div>
    <p></p>
    <blockquote></blockquote>
Climb-up: ^

    使用 ^ 在元素父节点生成新的元素节点
    操作符 ^ 的作用和 > 刚好相反
    
    用 > 可以在子级生成新的节点
    
    div+div>p>span+em
    会被转义成
    
    <div></div>
    <div>
        <p><span></span><em></em></p>
    </div>
用 ^ 可以在父级生成新的节点

    div+div>p>span+em^bq
    会被转义成
    
    <div></div>
    <div>
        <p><span></span><em></em></p>
        <blockquote></blockquote>
    </div>
    用n个 ^ ，就可以在第n父级生成新的节点

div+div>p>span+em^^^bq
    会被转义成
    
    <div></div>
    <div>
        <p><span></span><em></em></p>
    </div>
    <blockquote></blockquote>
Multiplication: *

使用 * 生成多个相同元素
    ul>li*5
    会被转义成
    
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
Grouping: ()

    圆括号 () 是Emmet的高级用法，用来实现比较复杂的DOM结构
div>(header>ul>li*2>a)+footer>p
会被转义成
    
    <div>
        <header>
            <ul>
                <li><a href=""></a></li>
                <li><a href=""></a></li>
            </ul>
        </header>
        <footer>
            <p></p>
        </footer>
    </div>
还可以嵌套使用圆括号 ()

(div>dl>(dt+dd)*3)+footer>p
    会被转义成
    
    <div>
        <dl>
            <dt></dt>
            <dd></dd>
            <dt></dt>
            <dd></dd>
            <dt></dt>
            <dd></dd>
        </dl>
    </div>
    <footer>
        <p></p>
    </footer>
属性操作符
属性操作符用来修改元素的属性

ID 和 CLASS

    Emmet给元素添加ID和CLASS的方法和CSS的语法类似
    div#header+div.page+div#footer.class1.class2.class3
    会被转义为
    
    <div id="header"></div>
    <div class="page"></div>
    <div id="footer" class="class1 class2 class3"></div>
自定义属性
    
    使用[attr]标记来添加自定义属性
    td[title="Hello world!" colspan=3]
    会被转义为

    <td title="Hello world!" colspan="3"></td>
元素编号

    使用 $ 操作符可以对重复元素进行有序编号
    ul>li.item$*5
    会被转义为

    <ul>
        <li class="item1"></li>
        <li class="item2"></li>
        <li class="item3"></li>
        <li class="item4"></li>
        <li class="item5"></li>
    </ul>
还可以用多个 $ 定义编号的格式

    ul>li.item$$$*5
    会被转义为

    <ul>
        <li class="item001"></li>
        <li class="item002"></li>
        <li class="item003"></li>
        <li class="item004"></li>
        <li class="item005"></li>
    </ul>
更灵活的编号方式

    使用 @ 修饰符可以改变编号的格式
    例如：

    在 $ 后面添加 @- 可以改变编号顺序

    ul>li.item$@-*5
会被转义成

    <ul>
        <li class="item5"></li>
        <li class="item4"></li>
        <li class="item3"></li>
        <li class="item2"></li>
        <li class="item1"></li>
    </ul>
在 $ 后面添加 @N 可以改变编号基数

    ul>li.item$@3*5
    会被转义为
    
    <ul>
        <li class="item3"></li>
        <li class="item4"></li>
        <li class="item5"></li>
        <li class="item6"></li>
        <li class="item7"></li>
    </ul>
还可以组合使用上面的修饰符

    ul>li.item$@-3*5
    会被转义为
    
    <ul>
        <li class="item7"></li>
        <li class="item6"></li>
        <li class="item5"></li>
        <li class="item4"></li>
        <li class="item3"></li>
    </ul>
文本操作符
Emmet使用 Text:{} 给元素添加文本内容

    a{Click me}
    会被转义为
    
    <a href="">Click me</a>
    注意： {text} 在Emmet中是被当成单独的元素来解析的，
    但当和其他元素结合使用时会有特殊的含义
    
例如：

    a{click} 和 a>{click 
    会输出相同的结果，但
    a{click}+b{here} 和 a>{click}+b{here} 
    输出的结果则不一样

    <!-- a{click}+b{here} -->
    <a href="">click</a><b>here</b>

    <!-- a>{click}+b{here} -->
    <a href="">click<b>here</b></a>
    在 a>{click}+b{here} 中，
     <b> 元素是<a>元素的子节点。
     这个就是区别：当 {text} 直接写在元素后面时，
     并不会改变父元素的上下文。

下面是一个更复杂的案例:

     p>{Click }+a{here}+{ to continue}
会被转义为

    <p>Click <a href="">here</a> to continue</p>
    而

    p{Click }+a{here}+{ to continue}
    则会被转义为

    <p>Click </p>
    <a href="">here</a> to continue
   
   [教程](http://wow.techbrood.com/tools/emmet/cs.html)

# 作业 
   练习 emment 能够熟练使用
   将浑河堡教会小给报告表 用emment方式展示。步骤要少