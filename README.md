# 我是标题1
## 我是标题2
### 我是标题3
*我是强调55555*

**我是加粗**

`function(){ return this.indec}`

>我是引用

惺惺惜惺惺

[点我去百度](http://www.baidu.com)

![图片了](https://ss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=2354832353,1872334409&fm=26&gp=0.jpg)
```<!doctype html>
<html>
<head>
	<meta charset="utf-8" />
	<title>网页换肤</title>
	<style type="text/css">
		* {
			margin: 0px;
			padding: 0px;
			list-style: none;
			text-decoration: none;
		}
		body {
			 margin: 10px;
			 background: #A3C5A8;

		}
		div {
			display: inline-block;
			cursor: pointer;
		}
		.redDiv {
			width: 6px;
			height: 6px;
			border: 4px solid red;
			background: red;
		}
		.greenDiv {
			width: 6px;
			height: 6px;
			border: 4px solid green;
			background: green;
		}
		.blackDiv {
			width: 6px;
			height: 6px;
			border: 4px solid black;
			background: black;
		}
		ul li {
			float: left;
			padding: 10px;
			border: 1px solid white;
			background: green;
		}
		ul li a {
			color: white;
		}
		.hysb{
			background:white;
		}
	</style>
</head>
<body>
	<div class="redDiv"></div>
	<div class="greenDiv"></div>
	<div class="blackDiv"></div>
	<ul>
		<li><a href="">新闻</a></li>
		<li><a href="">娱乐</a></li>
		<li><a href="">体育</a></li>
		<li><a href="">电影</a></li>
		<li><a href="">音乐</a></li>
		<li><a href="">旅游</a></li>
	</ul>
</body>
<script type="text/javascript" src="jquery-3.2.1.min.js"></script>
<script type="text/javascript">
	$('div').each(function(n,v){
		$(this).click(function(){
			$(this).addClass("hysb");
			$(this).parent().css('background',newnimabi.bg[n])
			$(this).parent().find("li").css('background',newnimabi.nav[n])
			$(this).siblings().removeClass("hysb");

		})
	})
	function nimabi(){
		this.bg = ['pink','#A3C5A8','#ccc']
		this.nav = ['red','green','black']
	}
	var newnimabi = new nimabi()
</script>
</html>```
