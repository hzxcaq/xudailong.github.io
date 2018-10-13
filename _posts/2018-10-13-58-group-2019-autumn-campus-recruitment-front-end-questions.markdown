---
layout: post
title:  "58集团2019秋季校园招聘前端类试题"
date:   2018-10-13 23:27:28 +0800
categories: jekyll update
---
一、选择题<br />
	1.([]instanceof Object)+10的输出结果是()<br />
	A.NaN B.11 C.10 D.都不是<br />
	2.localStorage.setItem('obj',{});<br />
	console.log(typeof loaclStorage.getItem('obj'));<br />
	最终的输出结果是()<br />	
	A. "Object " B."String" C."object" D."string"<br />
	3.const multi=(x=5,y=5)=>{<br />
	return x*y;<br />
	}<br />
	console.log(multi(3));<br />
	最终的输出结果是()<br />
	25 15 都不是 出错<br />
	4.display:nonehe visibility:hidden,说法错误的是()<br />
	A.visibility:hidden表示占据的空间依然存在<br />
	B.display:none表示隐藏元素，同时收回起存储空间<br />
	C.display:none和visibility:hidden都会处罚reflow<br />
	D.visibility:hidden和opcity:0都是视觉上透明<br />
	5.(typeof Array).slice(-1)输出结果是()<br />
	6.有代码<br />
	let{x=3,y=3,z=3}={<br />
	x:null<br />
	y:typeof(xy),<br />
	}<br />
	console.log(x,y,z);<br />
	最终的输出结果是()<br />
	7.下面哪一项不可以设置为一个BFC模式()<br />
	A.visibility:false B.overflow:hidden C.position:fixed D.float:none<br />
	8.现在有如下代码
	
	<body>
		<div class="test">
			<div class="dev1"></div>
			<dic class="dev2"></div>
		</div>
	</body>
	<style>
		*{
			margin:0;
			padding:0;
		}
		.test{
			margin:0 auto;
			background:#000;
			height:auto;
		}
		.test div{
			height:50px;
			margin:100px;
			background:#ff552e;
		}<br />
	</style>
	
问
(1)dev1和dev2的垂直距离<br />
(2)父元素和body的垂直距离<br />
(3)dev1与test的垂直距离<br />
9.现在有如下代码<br />
	<div class="parent" id="p"><br />
		<div class="child" id="c"></div><br />
	</div>对颜色设置下面哪一项权重最高()<br />
	A. .parent #c{color:#f40}<br />
	B.#p #c{color:#f40}<br />
	C..child {color:#f40 !important}<br />
	D..parent #p .child{color:#f40<br />
	10.let i=0;<br />
	for(;i<5;i+=1)<br />
	{<br />
		setTimeout(()=>{<br />
			console.log(i);<br />
		})<br />
	}<br />
	最终的输出结果是()<br />
	A.5 5 5 5 5<br /> 
	B.4 4 4 4 4<br />
	C.1 2 3 4 5<br />
	D.0 1 2 3 4<br />
二、简答题<br />
	1.简述你对MVVM的理解，描述（VUE、Angular、React三选一）的生命周期；
	
2.A标签伪类的写作顺序？为什么要按照顺序填写，如hover必须再link，visited之后，active必须再hover之后 link visited hover active<br />
	3.csrf和xss的区别<br />
	4.从var str='I am a string',str.toString出发，解释一下变量str可以调用toString的方法<br />
	5.如何对网站的文件和资源进行优化<br />
三、应用题<br />
	1.简述一下如何使用原生方法实现一个简单的事件管理器，该事件管理器有两个方法分辨是用于绑定事件的on(元素，时间类型，处理函数)和用于解绑事件的off(元素，时间类型，处理函数(可选 ))，说一下实现思路？<br />
	2.58同城手机官网需要增加一个横向轮播图来播放广告，现由你来设计这个轮播图组件，希望能够实现两个功能<br />
	(1)自动播放 (2)手指滑动左右切换图片<br />
四、编程题<br />
	现有A、B、C、D、E五个字母，其两两组合会得到固定值，值为AB=8,AC=7,AD=9,BC=3,BD=2,BE=4,CD=0,CE=5,DE=6(例如A、B、C其组合为AB、AC、BC，组合值8+7+3=18)，请在其中找出三个字幕，使其两两组合值总和最大。<br />