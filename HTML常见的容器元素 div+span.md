<h1>HTML常见的容器元素 div+span</h1>

div 块级元素 ：可以对所有文本设置各种样式格式

                   块级元素要独占一行的，

span 行内元素：  只能对部分一小段文本内容设置样式或格式，可以解决代码冗余问题

                            行内元素不会以新行开始

<div style="color:#0000ff">
    <h1>
        div样式的标题
    </h1>
    <p>
        div样式的文本
    </p>
</div>

<h2>
    文本内容用span设置部分一小段文本内容<span style="color:red">文本内容为</span>红色
</h2>

<h1>二、html布局，使用div+span容器元素编辑</h1>

<div id="container" style="width:500px">
    <div id="header" style="background-color:#ffff00;">
        <h2 style="margin-bottom:0;">主要的网页标题</h2></div>
    <div id="menu" style="background-color:#ffd700;height:200px;width:100px;float:left;">
    <b>菜单：前端前期所学语言</b><br>
    HTML<br>
    CSS<br>
    Javascript</div>
<div id="content" style="background-color:#eeeeee;height:200px;width:400px;float:left;">
    内容在这里<br>
</div>  
<div id="footer" style="background-color:#ffa500;clear:both;text-align;center;">
    底部的一些版权和权限
</div>



<h2>三、HTML form 表单的创建</h2>

<form action="http://www.taobao.com" method="post">
    <p>
        账号：<input type="text"></p>
    <p>
        密码：<input type="text"></p>
    <p>
        内容：<textara></textara>
    </p>
    <p>
        <input type="submit" value="登录">
        <input type="submit" value="注册">
    </p>
</form>



<form action="">
    <input type="text" size="30"><br>
    <textarea></textarea><br>
    <input type="text" size="10"><br>
    <input type="submit" value="文本"><br>
    <input type="sex" name="name" value="your name">
</form>

