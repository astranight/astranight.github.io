<html lang="en">
<meta charset="utf-8">
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
<meta http-equiv="content-type" content="text/html;charset=utf-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
<title>生日快乐</title>
 
<link rel="stylesheet" type="text/css" href="Happybirthday/css/style.css">
 
<script type="text/javascript" src="Happybirthday/js/jquery.min.js"></script>
<script type="text/javascript" src="Happybirthday/js/vector.js"></script>
<script >
	function myfunction()
 
	{
	
	var x=document.getElementById("entry_name").value;
	var y=document.getElementById("entry_password").value;
	if(x==""||y=="")
		{alert("You won't forget your name, will you? (～￣(OO)￣)ブ")}
	else  if (x=="ABC"&& y=="123")
		{window.location.href="SecondLucky/LuckyEvertime.html";}
	else {alert("You won't forget your name, will you? (≧∇≦)ﾉ");}}
		</script>
 
 
 
</head>
<body>
	<audio autoplay="autoplay" loop="loop" preload="auto"
 
            	src="弹奏微风.mp3"></audio>
 
<div id="container">
	<div id="output">
		<div class="containerT">
			<h1>小意是个小傻子</h1>
			<h1>每天都在找脑子</h1>
			<h1>(￣▽￣)～■干杯□～(￣▽￣)</h1>
			<form class="form" id="entry_form">
				<input type="text" placeholder="账号" id="entry_name" >
				<input type="password" placeholder="密码" id="entry_password">
				
				
					<button type="button" id="entry_btn" type="button" οnclick="myfunction()">Click me!(๑•̀ㅂ•́)و✧</button> 
	
				<div id="prompt" class="prompt"></div>
			</form>
		</div>
	</div>
</div>
 
 
 
</body>
</html>
