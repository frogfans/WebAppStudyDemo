# WebAppStudyDemo

A demo to study web app development.

---
**Main:**

![](https://github.com/frogfans/WebAppStudyDemo/blob/master/res/main.jpg?raw=true)

---
**If you click button "+1s" or image, then it shows a dialog:**

![](https://github.com/frogfans/WebAppStudyDemo/blob/master/res/dialog.png?raw=true)

<html>
<head>
	<link rel="stylesheet" type="text/css" href="demo.css">
	<meta charset="utf-8" />
		<title>真正的粉丝</title>
	</head>
	<body>
		<script src="demo.js"></script>
		<div id="div1">
			<h1>一级标题</h1>
			<h2>二级标题</h2>
			<h3>三级标题</h3>
			<h4>四级标题</h4>
			<h5>五级标题</h5>
			<h6>六级标题</h6>
			<p>段落</p><br>换行
			<hr id="tips">水平线<br>
			<!-- 注释 -->
			<b>粗体</b><br>
			<code>计算机代码</code><br>
			<em>强调</em><br>
			<i>斜体</i><br>
			<kbd>键盘输入</kbd><br>
			<pre>预格式化文本   三个空格</pre><br>
			<small>小文本</small><br>
			<strong>重要文本</strong><br>
		</div>
		<div id="div2">
			缩写<abbr title="World Health Organization">WHO</abbr><br>
			<bdo dir="rtl">从右到左显示</bdo><br>
			<del>这个已删除</del><br>
			<ins>这个新插入</ins><br>
			<sup>这是上标</sup><sub>这是下标</sub>
			<a href="https://www.baidu.com/">baidu</a>
			<blockquote cite="http://frogfans.github.io/">too young too simple, sometimes naive.</blockquote>
			引用自<cite>frogfans</cite><br>
			点我发现新大陆: <a href="http://frogfans.github.io/">frogfans</a><br>
			点击图片跳转: <br>
			<a href="https://frogfans.github.io/" target="_blank"><img id="img1" src="res/logo.png" alt="图片违规不予显示。"></a><br>
			<a href="#tips">跳到水平线</a>
			<ul>
				<li>真正的粉丝</li>
				<li>即使我不说</li>
				<li>也知道是谁</li>
			</ul>
			<ol>
				<li>too young too simple</li>
				<li>sometimes naive</li>
				<li>excited</li>
			</ol>
		</div>
		<div id="div3" padding="0px">
			<table border="2">
				<caption>人生经验</caption>
				<thead>
					<tr>
						<th>视察二院</th>
						<th>谈笑风生</th>
						<th>怒叱记者</th>
					</tr>
				</thead>
				<tbody>
					<tr>
						<td>另请高明吧</td>
						<td>time flies very fast</td>
						<td>无可奉告</td>
					</tr>
					<tr>
						<td>历史的行程</td>
						<td>very frankly speaking</td>
						<td>闷声大发财</td>
					</tr>
					<tr>
						<td>微小的工作</td>
						<td>big mistake!</td>
						<td>提高自己的知识水平</td>
					</tr>
				</tbody>
				<tfoot>
					<tr>
						<td>天若有情天亦老</td>
						<td>我为长者续一秒</td>
						<td id="td1"><input type="button" value="  +1s  " onclick="donateLife()"></td>
					</tr>
				</tfoot>
			</table>
			<frameset cols="100%">
			<frame src="https://frogfans.github.io">
			</frameset>
			<form>
				<p>你现在的心情是：</p>
				<input type="radio" name="emotion" value="regius">钦定<br>
				<input type="radio" name="emotion" value="angry">angry<br>
				<input type="radio" name="emotion" value="excited">excited<br>
				<input type="button" onclick="selectEmotion()" value="Choose">
			</form>
			<br>
		</div>
		<div id="div4">
			<p>一人续一秒，我蛤永不倒：</p>
			<img id="img2" src="res/frog.jpeg" alt="图片违规不予显示。" onclick="donateLife()">
			<div id="div5">
				<strong>Got Life:</strong>
				<b id="life">0</b>
			</div>
			<br><br>
			End<br><br>
		</div>
	</body>
</html>