  
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
		<img src="woodcutter.jpg">
	</div>
	<div id="Job">
	<h3>나무꾼</h3>
	<p>나무꾼이란 벌채 산업에서 임산물로 가공될 나무를 일차적으로 수확 및 운송하는 자를 말한다.</p>
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
