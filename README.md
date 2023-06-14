# yuyu.github.io
<!DOCTYPE html>
<html>
<head>
	<title>健身房信息展示</title>
	<style>
		body {
			font-family: Arial, sans-serif;
			background-color:rgba(109,114,216,0.7);
		}
		h1 {
			text-align:center;
			margin-top: 50px;
			font-size: 40px;
			color: #4d4d4d;
		}
		h2 {
			font-size: 30px;
			color: #4d4d4d;
			margin-top: 50px;
		}
		p {
			font-size: 18px;
			color: #666;
			line-height: 1.5;
		}
		.container {
			max-width: 1200px;
			margin: auto;
			padding: 50px;
			background-color:rgba(176,242,225,1.00);
			box-shadow: 0px 0px 20px rgba(0, 0, 0, 0.1);border-radius: 40px;
		}
		.section {
			margin-top: 50px;
		}
		.grid-container {
		    display: grid;
		    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
		    grid-gap: 30px;
		  	margin-top: 50px;
		}
		.grid-item {
			background-color: #fff;
			border-radius: 5px;
			box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
			padding: 20px;
			text-align: center;
		}
		img {
			max-width: 100%;
			height: auto;
			border-radius: 5px;
			margin-bottom: 20px;
			height: 200px;
			width: 300px;
		}
header {
	background-color: #333;
	color: #fff;
	padding: 10px 20px;
	border-radius: 20px;
	margin-bottom: 10px;
}

nav ul {
	margin: 0;
	padding: 0;
	list-style: none;
	display: flex;
}

nav li {
	margin-right: 20px;
	margin: 10px;
}

nav a {
	color: #fff;
	text-decoration: none;
}
		footer {
			background-color: #333;
			color: #fff;
			padding: 20px;
			text-align: center;
			position:relative;
			margin-top: 10px;
			bottom: 0;
			border-radius: 20px;
		}
		.back-to-top {
  display: none; /* 隐藏按钮 */
  position: fixed; /* 在屏幕上固定位置 */
  bottom: 20px; /* 距离底部 20 像素 */
  right: 20px; /* 距离右边 20 像素 */
  background-color: #333; /* 背景颜色 */
  color: #fff; /* 文字颜色 */
  border-radius: 50%; /* 圆角 */
  padding: 10px 15px; /* 按钮内边距 */
  font-size: 16px; /* 字号 */
  cursor: pointer; /* 光标样式 */
  z-index: 999; /* 显示在页面上的顺序（越大越上面） */
}

.back-to-top:hover {
  background-color: #fff; /* 鼠标悬停状态下的背景颜色 */
  color: #333; /* 鼠标悬停状态下的文字颜色 */
}
		
	</style>
</head>
<body>
	<a href="#" class="back-to-top">返回顶部</a>
	<header>
		<nav>
			<ul>
				<li><a href="../html/index.html">首页</a></li>
				<li><a href="../html/CurriculumManagement.html" target="_self">课程管理</a></li>
				<li><a href="../html/equipment.html">设备管理</a></li>
				<li><a href="../html/Financialmanagement.html">财务管理</a></li>
				<li><a href="../html/individual.html">个人信息</a></li>	
				<li><a href="../html/Coursepresentation.html">课程展示</a></li>
				<li><a href="../html/Courseranking.html">健身房排行</a></li>
				<li><a href="../html/member.html">会员主页</a></li>
				<li><a href="../html/Datastatistics.html">健身房数据统计</a></li>
				<li><a href="../html/feedback.html">意见反馈</a></li>
				<li><a href="#">退出</a></li>
			</ul>
		</nav>
	</header>
	<div class="container">
		<h1>首页</h1>
		<div id="contactModal" style="display: none;"></div>
		<section class="section">
			<h2>历史</h2>
			<p>本健身房成立于2001年，至今已经服务了数千位会员。</p>
			<p>我们始终秉承“让健康成为生活的一部分”的理念，为每一位顾客提供高质量的健身服务。</p>
		</section>

		<section class="section">
			<h2>精品课程</h2>
			<div class="grid-container">
				<div class="grid-item">
					<img src="../img/img12.jpg" >
					<h3>瑜伽课程</h3>
					<p>由知名瑜伽教练亲自授课，适合所有人群，能有效缓解身心压力。</p>
				</div>
				<div class="grid-item">
					<img src="../img/img13.jpg" >
					<h3>动感单车</h3>
					<p>激情骑行，有氧运动，让你在音乐的节拍中享受运动带来的快感。</p>
				</div>
				<div class="grid-item">
					<img src="../img/img14.jpg" >
					<h3>肌力训练</h3>
					<p>通过器械和自重训练，让你的肌肉得到全面锻炼，提高身体素质。</p>
				</div>
			</div>
		</section>

		<section class="section">
			<h2>优秀教练</h2>
			<div class="grid-container">
				<div class="grid-item">
					<img src="../img/img30.jpg" >
					<h3>张教练</h3>
					<p>从业10年，拥有丰富的教学经验，能够根据不同会员的身体情况制定科学的运动计划。</p>
				</div>
				<div class="grid-item">
					<img src="../img/img31.jpg" >
					<h3>李教练</h3>
					<p>擅长瑜伽、普拉提等运动，有良好的口碑和信誉。</p>
				</div>
				<div class="grid-item">
					<img src="../img/img32.jpg" >
					<h3>王教练</h3>
					<p>专业的肌肉训练指导，为你的身体打好健康基础。</p>
				</div>
			</div>
		</section>

		<section class="section">
			<h2>优秀会员</h2>
			<div class="grid-container">
				<div class="grid-item">
					<img src="../img/img35.jpg" style="height: 400px;width: 300px">
					<h3>小刘</h3>
					<p>在本健身房坚持锻炼已经1年，已经成功减掉了20斤体重。</p>
				</div>
				<div class="grid-item">
					<img src="../img/img33.jpg" style="height: 400px;width: 300px">
					<h3>小张</h3>
					<p>因为工作压力大，总是感到疲劳，加入本健身房后，身体状态明显改善，精神更加充沛。</p>
				</div>
				<div class="grid-item">
					<img src="../img/img34.jpg" style="height: 400px;width: 300px">
					<h3>小王</h3>
					<p>通过学习瑜伽和冥想等技巧，成功调节了情绪，收获了更加健康的人生。</p>
				</div>
			</div>
		</section>

		<section class="section">
			<h2>优秀员工</h2>
			<div class="grid-container">
				<div class="grid-item">
					<img src="../img/img36.jpg" style="height: 400px;width: 300px">
					<h3>张经理</h3>
					<p>管理有方，团队凝聚力强，是本健身房不可或缺的核心员工。</p>
				</div>
				<div class="grid-item">
					<img src="../img/img37.jpg" alt="" style="height: 400px;width: 300px">
					<h3>赵前台</h3>
					<p>服务热情周到，为每一位顾客提供贴心的咨询和指导。</p>
				</div>
				<div class="grid-item">
					<img src="../img/img38.jpg" alt="" style="height: 400px;width: 300px">
					<h3>刘清洁工</h3>
					<p>勤奋努力，清洁卫生得体，保证了健身房环境的整洁和卫生。</p>
				</div>
			</div>
		</section>
		 
	</div>
	  	<footer>
		<p>版权所有 © 2001 yuyu 四川工业科技学院-2021级软件工程专业&nbsp;李余</p>
	</footer>
	<script>
	window.onscroll = function() {scrollFunction()};

function scrollFunction() {
  if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
    document.querySelector('.back-to-top').style.display = 'block'; // 显示按钮
  } else {
    document.querySelector('.back-to-top').style.display = 'none'; // 隐藏按钮
  }
}

function topFunction() {
  document.body.scrollTop = 0; // Safari
  document.documentElement.scrollTop = 0; // Chrome, Firefox, IE and Opera
}
	
	</script>
</body>
</html>
