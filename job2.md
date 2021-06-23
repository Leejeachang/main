<!doctype html>
<html>


<head>
	
	<meta charset="utf-8">

	<style>
	/*마진,패딩초기화*/
	*{
		padding: 0;
		margin: 0;
	}

	/*float속성을 왼쪽으로*/
	#image{
		float: left;
		margin: 30;
	}

	/*직업 소개*/
	#Job{
		float: left;
		/*margin: 30px;*/
		margin-top: 30px;

	}

	#menu
	{
		float: right;
		margin: 30px;
	}
	/*Ll스타일 정의*/
	li{
		list-style-type: none;
		padding: 10px;
		font-weight: bold;
		border-bottom: dashed 2px gray;
	}

	</style>

</head>

<title>job2</title>

<body>
	

	<div id='image'>
		<img src="doctor.jpg">
	</div>
	<div id="Job">
	<h3>의사</h3>
	<p>의사는 현대의학의 전문가로서 인체의 질병, 손상, 각종 신체 혹은 정신의 이상을 연구하고 진단, 치료함으로써 인간의 건강을 증진하고 유지하며 회복시키는 일을 수행하는 사람을 말한다.</p>
	</div>
	
	<ul id="menu">
		<li><a href="job1.html">요리사</a></li>
		<li><a href="job2.html">의사</a></li>
		<li><a href="job3.html">소방관</a></li>
		<li><a href="job4.html">광부</a></li>
		<li><a href="job5.html">경찰</a></li>
		<li><a href="job6.html">나무꾼</a></li>
	</ul>

	


</body>
</html>
