# HtmlCssJsLab
codecademy网站的实验代码

<strong>xxxxxxxx<strong>加粗
<!DOCTYPE html>放在第一行说明浏览器语言（这个是HTML）
<html>放第二行用来开始HTML项目
</html>放项目最后一行，表示结束
<><>成对出现，并且里面的叫做tag(标签)，有开始就有结束并且最后一个<>跟最开始一个</>相互对应
HTML文件分为head&body
head包括文件的标题/主题，用在<head></head>之间的是head的内容，而在这二者之间我们还可以<title></title>之间填写标题。
head之后是body，用<body></body>,body内容可显示查看，body中<p></p>之间的内容表示一段
 
body的标题是heading tags标记，比如<h1></h1>之间能显示大字。
具体用法
<body>
	<h1>1	<p>2</p><p>3</p></h1>
</body>
显示 
字体•  
<h1> - The CEO
•  <h2> - VP
•  <h3> - Director
•  <h4> - Middle management
•  <h5> - Lowly assistant
•  <h6> - Gets coffee for everyone
<h1>1	<h3><p>2</p></h3><h5><p>3</p><h5></h1> 
链接传送门（包括描述）<a href="http://www.codecademy.com">My Favorite Site!</a>
图片显示<img src="http://img4.imgtn.bdimg.com/it/u=172854348,2169551524&fm=21&gp=0.jpg" />
图片的网页链接方法
<a href="http://www.codecademy.com/">
		<img src="http://s3.amazonaws.com/codecademy-blog/assets/f3a16fb6.jpg" />
		</a>
订单（有序）列表
<ol>
			<li>Raindrops on roses</li>
			<li>Whiskers on kittens</li>
			<li>Bright copper kettles</li>
			<li>Warm woolen mittens</li>
		</ol>
无序列表
<ul>
    <li>Cheese</li>
    <li>Sour Cream</li>
</ul>
注释（不显示）
<!-- Make me into a comment. -->
字体大小
<p style="font-size: 10px"> Some text for you to make tiny! </p>
字体颜色+大小改变
<h1 style="color: green; font-size:16px">
字体
style="font-family: Arial"
加粗<strong></strong>
变斜<em></em>
背景颜色background-color:yelow
表格<table></table>
行<tr></tr>
没有列，用行来表示
列<td></td>
表头
<thead>
                <tr>
                <th>Famous Monster</th>
                <th>Birth Year</th>
                </tr>
      </thead>
       <tbody></tbody>
合并列<th colspan="2">合并2列
页面分区：<div>
最小的字体及其他变化<span></span>
css的stylesheet.css
<link type="text/css" rel="stylesheet" href="stylesheet.css"/>
<style>
			p {
				color: purple;
			}
		</style>
自开自合：<img src="web address"/>
<link type="text/css" rel="stylesheet" href="CSS file address"/>
css一般用法
selector {
    property: value;
}
16进制颜色表示：#1111
可尝试第一个，若电脑中没有则使用第二个，以此类推font-family: Times, serif;
border可兼容多个属性值比如border:1px solid black.
button:
div
{
    height: 50px;
    width: 120px;
    border-color: #6495ED;
    background-color: #BCD2EE;
    border-style:solid;
    border-width: 2px;
border-radius : 5px;按钮的角圆滑
margin : auto;
    text-align : center;
}
可以用多个来指定位置
例如div div p{}指<div><div><p>xxxxxxxxxx</p></div></div>

*{}可以指定所有个体
div > p指直接从属于div的p
越详细的selectors执行优先级越高
优先级最高的 classes  &  IDs
.classesname;#idname
Pseudo-class selectors可以表明状态（例如网页没点蓝，点了紫）
a:link: An unvisited link.
a:visited: A visited link.
a:hover: A link you're hovering your mouse over.
first-child：第一个项目
nth-child（）：括号内是第几个项目
p:nth-child(5) {
    font-size :22px;
}
(display:inline-block and margin-left: 5px). 
block: This makes the element a block box. It won't let anything sit next to it on the page! It takes up the full width.
inline-block: This makes the element a block box, but will allow other elements to sit next to it on the same line.
inline: This makes the element sit on the same line as another element, but without formatting it like a block. It only takes up as much width as it needs (not the whole line).
none: This makes the element and its content disappear from the page entirely
margin-top: /*some value*/
margin-right: /*some value*/
margin-bottom: /*some value*/
margin-left: /*some-value*/

margin: 1px 2px 3px 4px; will set a top margin of 1 pixel, a right margin of 2, a bottom of 3, and a left of 4.
padding-top: /*some value*/
padding-right: /*some value*/
padding-bottom: /*some value*/
padding-left: /*some-value*/
padding: value value value value;

element {
    clear: /*right, left, or both*/
}







