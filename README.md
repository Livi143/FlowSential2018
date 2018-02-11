# FlowSential2018
FlowSential Webpage
T9Flowsential_welcome18html
<!DOCTYPE html>
<html>
<head>
	<meta charset="UTF-8">
		<title>FlowSential Welcome</title>
<!-- Latest compiled and minified CSS -->
 		<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">

 <!-- This is the wave image
jQuery library -->
 		<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>

 <!-- Latest compiled JavaScript -->
 		<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
		<link rel = "stylesheet" href="FS.css">
</head>  <!-- Latest compiled and minified CSS -->

<body>
	<h1>Welcome to FlowSential!</h1>

	<img src="FlowSentialWave.jpg" alt="japanese_wave" width="500" height="600">

 <div class="row">
 	<div class="col-md-4">

 	</div>
 	<div class="col-md-4 LOGIN">

   <!-- Provides extra visual weight and identifies the primary action in a set of buttons -->
	 	<br>
		<button type="button" class="btn btn-primary">Create Account</button>
		<!-- Secondary, outline button -->
		<button type="button" class="btn btn-secondary">Login</button>
 </div>
 <div class="col-md-4">

 </div>
</div>
		<br>

		<br>
</div>
	</div>
</div>
</body>
</body>
</html>

FS.css
body{
 max-width: 1000px;
 margin: auto;
 background-color: pink;
}
h1{
 color: deeppink;
 text-align: center;
}
body{}
img {
display: block;
 margin-left: auto;
 margin-right: auto;

}
.LOGIN {text-align: center;}


<!DOCTYPE html>
<html>
<head>
	<meta charset="UTF-8">
		<title>FlowSential Welcome</title>
<!-- Latest compiled and minified CSS -->
 		<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">

 <!-- This is the wave image
jQuery library -->
 		<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>

 <!-- Latest compiled JavaScript -->
 		<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
		<link rel = "stylesheet" href="FS.css">
</head>  <!-- Latest compiled and minified CSS -->
<body>
<nav class="navbar navbar-inverse">
 <div class="container-fluid">
   <div class="navbar-header">
     <a class="navbar-brand">Flow Sential</a>
   </div>
   <ul class="nav navbar-nav">
     <li class="active"><a href="T9Flowsential_home18.html#">Home</a></li>
     <li><a href="T9Flowsential_aboutus.html#">About us</a></li>
     <li><a href="#">Your profile</a></li>
   </ul>
 </div>
</nav>
<div class="jumbotron">
 <h1>Natural Family Planning</h1>
</div>
<p>Sometimes contraception is not easily accessible or a feasibility. Luckily, you can avoid pregrancy by strigently tracking your basal body temperature along with a hanful of other variables.
Your body temperature will flucutate every so slightly throughout your cycle. Heavy drinking, losing sleep, smoking, consuming caffeine, and using a heating pad can affect your basal temperature. Typically, a women's body temperature will range from 96º-98º Fahrenheit before ovulation, and ranges from 97º-99º Fahrenheit after ovulation has occured. In order to effectivly use natural family planning, you should take your body temperature at the same time every day- it should be the FIRST Thing that you do in the morning. Please check the boxes below for whichever variable apply to you, and enter your basal temperature. </p>

<p> Please click on the box if you answer "Yes" </p>

<label><input type="checkbox" value="Did You Get 8 Hours of Sleep?">Did You Get 8 Hours of Sleep?</label>
</div>
<div class="checkbox disabled">
<label><input type="checkbox" value="Did You Party Last night?" >Did You Party Last night?</label>
<div class="checkbox">
  <label><input type="checkbox" value="Have You Used a Heating Pad Today?">Have You Used a Heating Pad Today?</label>
</div>
<div class="checkbox">
  <label><input type="checkbox" value="Have You Consumed Coffee Before Taking Your Temperature?">Have You Consumed Coffee Before Taking Your Temperature?</label>
</div>
<div class="checkbox">
  <label><input type="checkbox" value="Have You Consumed Nicotine Before Taking Your Temperature?">Have You Consumed Nicotine Before Taking Your Temperature?</label>
</div>
</div>

T9Flowsential_home18.html
<div>
<form>
Quantity Celcius (between 35.00 and 37.00):

<input type="number" name="quantity" min="1" max="5">

Quantity Fahrenheit (between 96.00 and 102):
<input type="number" name="quantity" min="1" max="5">
</form>
</form>
</div>
</body>
</html>
T9Flowsential_home18.css
.jumbotron{
 background-color: papayawhip;
}

.navbar{
 background-color: indianred;
}
T9Flowsential_aboutus.html
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>
<p> We believe that everyone deserves to have access to knowlege and wide spread access to safe contraception regardless of where they live or their income. The more tools that women have the better their communities become. Our long term goals for FlowSential are to create a robust algorithm that will serve as an effective fertility awareness tool, offer in depth education regarding natural family planning and contraceptive options, and reproductive health. Ideally, we would also like to eventually create an mobile freindly platform that would be availble offline as many of our target users don't have reliable access to the internet. 501c3 Status and the ability to raise funds to have server access and distribute cycle beads is also on the agenda.   .</p>
<img src="https://files.slack.com/files-pri/T0DQ5U8G2-F977YPT27/screen_shot_2018-02-11_at_9.35.59_am.png" alt="Diana Lopez">
<div>
<img src="https://lh3.googleusercontent.com/MdxP2mNjxDyd4VQ0tdCt5pg_5auB1Xbm8O0bH8ljcHJO-Ztek6-udfTHT1xCD_sznFkVSvE=s85" alt="Olivia Fontanese">
</div>
</html>

T9Flowsential_aboutus.css
