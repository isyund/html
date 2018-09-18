**文本格式化**

<b>加粗

<i>斜体

<code>电脑自动输出

<sub>下标

<sup>上标

<br>

换行

<ins>插入文字

<del>删除文字

<p>段落

<a href="">该链接</a>链接



html链接使用target属性，可以定义链接在何处显示，例如定义target属性为_blank，链接将在新的窗口打开。&quot;_blank&quot;

在当前页面链接到指定位置

<a href="#C4">查看章节4</a>

target 属性 _blank,_parent,_self,_top,framename 规定页面中供所有超链接和表单在何处打开，该属性会被每个链接中的target属性覆盖

<head> 定义文档的信息

</head>

1. title定义文档的标题
2. base定义页面链接标签的默认链接地址
3. link定义一个文档和外部资源的关系
4. meta定义html文档中的元数据
5. script 定义客户端脚本文件
6. style 定义html文档的样式文件



**background-color 定义一个元素的背景颜色，如**

<body style="background-color:yellow;">

<h2 style="background-color:red;">这是一个标题</h2>

<p style="background-color:green;">这是一个段落</p>

</body>

**字体，字体颜色，字体大小**

font-family 字体， color 颜色， font-size字体大小

<h1 style="background-color:red;font-family:verdana;">一个标题</h1>

<p style="background-color:yellow;font-family:arial;color:red;font-size:20px;">这是一个段落</p>

**文本对齐方式**

text-align文字对齐 属性指定文本的水平与垂直对齐方式

<h1 style="background-color:red;font-family:verdana;color:green;font-size:40px;text-align:center;">居中对齐的标题</h1>

<p style="text-align:center;">段落</p>

**图像**

<img>图像

<map>地图

</map>

<area>地图中可点击的区域

**表格标签**

1. table 表格
2. th 表格的表头
3. tr 表格的行
4. td 表格单元
5. caption 表格标题
6. colgroup 表格列的组
7. col 表格列的属性
8. thead 表格的页眉
9. tbody 表格的主体
10. tfoot 表格的页脚

**列表标签**

ol 有序列表

<h4>有序列表</h4>

<ul>
    <li> 有序列表1</li>
    <li>有序列表2</li>
    <li>有序列表3</li>
</ul>



ul 无序列表

<h4>无序列表</h4>

<ul>
    <li>无序列表1</li>
    <li>无序列表2</li>
    <li>无序列表3</li>
</ul>



li 列表项

dl列表 

dt 自定义列表项目

dd 自定义列表项的描述

**区块**

大多数html元素被定义为块级元素或内联元素。

块级元素：通常是以新行来开始，有<h1>,<p>,<ul>,<table><div>

div属于块级元素

<div style="color:blue;">
    <h3>
        这是一个在div元素中的标题。
    </h3>
    <p>
        这是一个在div元素中的文本
    </p>
</div>



内联元素：通常不是以新行来开始的，有<b>,<td>,<a>,<img>,<span>

span属于内联元素

<p>我的母亲也有<span style="color:blue;font-weight:bold">蓝色</span>的眼睛。</p>

**表单标签**

多数情况下被用到的表单标签是输入标签"input",输入类型由类型属性type来定义

文本区域：

<form>
    first name:<input type="text" name="firstname"><br>
    last name:<input type="text" name="lastname">
</form>

文本框：

<textarea rows="10" cols="30">
    我是一个文本框
</textarea>



密码字段：

<form>
    password: <input type="password" name="pwd">
</form>

单选按钮radio buttons

<form>
    <input type="radio" name="sex" value="male">male<br>
    <input type="radio" name="sex" value="female">female
</form>

复选框checkboxs

<form>
    <input type="checkbox" name="vehicle" value="bike">i have a bike <br>
    <input type="checkbox" name="vehicle" value="car"> i have a car
</form>

提交按钮 submit button

<form name="input" action="html_action.php" method="get">
    username:<input type="text" name="user">
    <input type="submit" value="submit">
</form>

简单的下拉按钮

<form action="">
    <select name="cars">
        <option value="1">1</option>
        <option value="2">2</option>
        <option value-"3">3</option>
    </select>
</form>
      

form 供用户输入的表单

input 输入域

textarea 文本域、

label 定义了input元素的标签，一般为输入标题

fieldset 定义了一组相关的表单元素，并使用外框包含起来

legend 定义了fieldset元素的标题

select 定义了下拉选项列表、

optgroup 定义选项组】

option 定义下拉列表中的选项

button 定义一个点击按钮

datalist 制定一个预先定义的输入控件选项列表

key.gen定义了表单的密钥对生成器字段

output 定义一个计算结果

带边框的表单：

<form action="1">
    <fieldset>
        <legend>
            边框里元素的标题
        </legend>
        姓名:<input type="text" size="30"><br>
        性别:<input type="text" size="30"><br>
        电话:<input type="text" size="30">
    </fieldset>
</form>

带有输入框和确认按钮的表单

<form action="">
    姓名：<input type="text" name="姓名" value="董培云"><br>
    性别： <input type="text" name="性别" value="女"><br>
    <input type="sunmit" value="submit">
</form>

带有复选框的表单

<form action="">
    <input type="checkbox" name="vehicle[]" value="apple">i have an apple<br>
    <input type="checkbox" name="vehicle[]" value="bile">i have a bike<br>
    <input type="submit" value="提交">
</form>

**框架**

iframe src="url" 该URL指向不同的网页

<ifame src="demo_ifame.htm" widtn="200" height="200"></ifame>

**颜色**

<p style="background-color:rgb(0,0,0)">
</p>



<p style="background-color:rgba(255,255,0,0.5)"
</p>



**脚本**

script

<script>
    document.write("Hello World!")
</script>

<script>
    document.write("hello world!")
</script>



**字符实体**

一些键盘上找不到的字符可以使用字符实体来替换



虽然html不区分大小写，但实体字符对大小写敏感

空格 $nbsp

小于号&it

大于号&gt

&号&amp

引号&quot

撇号&apos

人民币&yen

.........

**URL**

http 超文本传输协议               以http://开头的普通网页。不加密

https 安全超文本传输协议     安全网页，加密所有信息交换

ftp  文件传输协议                     用于将文件下载或上传至网站

file                                              计算机上的文件