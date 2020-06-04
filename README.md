<!DOCTYPE html>
<html>
<head>
	<title>JIANI TIAN</title>
	<meta name="description" content="Happy Birthday/Grad Jiani! I love you!">
	<link href="https://fonts.googleapis.com/css?family=Raleway&display=swap" rel="stylesheet">

	<style>
		html {
			scroll-behavior: smooth;
		}
		@font-face {
			font-family: "BLUDHAVEN"; 
			src: url("BLUDHAVEN.ttf")
		}

		body, html {
			margin: 0px;
			height: 100vh;
  			overflow: hidden;
  			width: 100vw;
		}
		a {
			color: #515151;
			font-family: 'Raleway', sans-serif;
		}

		#container {
			overflow-x: hidden;
			height: 100vh;
			scroll-snap-type: y mandatory;
			margin: 0;
			padding:0;
		}
		section {
			scroll-snap-align: start;
			height: 100vh;
			position: relative; 
		}
		#page1 {
			background-color: #ebd9d8/*d1aeac*//*efe9e8*/;
			height: 100vh;
			width: 100%;
			
		}
		#first{
			top: 55vh;
			right:12vw ;
		}
		#last{
			top:67vh;
			left: 14vw;
		}
		
		#mainPic {
			width: 100%;
		    position: relative;
			top: 50vh;
			transform: translateY(-55%);
		}
		
		#mainPicContainer {
			width: 31%;
			/*height: 600px; */
			margin-left: auto; 
			margin-right: auto; 
			
		}
		#strike{
			width: 100%;
			background-color: white/*424242*//*424c7a*//*394475*/;
			height: 10%;
			position:absolute;
			top: 30vh;
		}
		h1 {
			font-family: 'BLUDHAVEN', sans-serif;
			font-size: 6em; 
			font-weight: 200; 
			margin: 0px;
			text-align: center;
			width: 100%; 
			/*position: relative;
			bottom: 20vh;
			*/
			color: white;
			position: absolute;
			
			/*left: 10vw;*/
			/*transform: translateY(24%);*/
			
			
   		}
   		#mainMenu{
   			position: absolute;
			top:90vh;  
			left: 50vw; 	
			transform: translateX(-50%);	
			width:40%;
			text-align: center;	
   		}
   		#mainMenu a{
   			margin: 1%;
   			/*font-family: 'BLUDHAVEN';*/
   			font-size: 130%;
   			text-decoration: none;
   		}
   		#mainMenu a:hover{
   			text-decoration: underline;
   			color: black;
   		}

		#page2 {
			background-color: #f8f4f1/*b8afba*//*a49fa5*//*f8f4f1*/;
			height: 100vh;
		}
		.page2circle {
   			position:absolute;
   			top: 0px;
   			right: 1%; 
   			height: 10%;
   			width: 10%;
   			transition: all 0.5s 0s;
   			text-align: right;
   		}
 
   		.page2circle:hover {
   			border-radius: 0%;
   			bottom: 0px;
   			right: 1%; 
   			font-size: 1em; 
   		}

   		.page2circle p {
   			font-family: "BLUDHAVEN";
   			color: #d15a4b;
   		}
		.page2circle .menu {
   			opacity: 0;  
   			margin-top:-20%; 		
   		}
   		.page2circle:hover .menu {
   			opacity: 1;
   			transition: all 0.5s 0.3s;
   			transform:translateY(25%);

   		}
		#col1 {
			width: 27%;
			float: left; 
			background-color: white; 
			height: 100vh;
		}
		#col1 img{
			margin-left: 5%; 
			margin-bottom: 3%;
		}
		h2 {
			font-family: 'BLUDHAVEN', sans-serif;
		}
		#col1 h2 {
			
			padding-top: 45vh;
			text-align: center; 
			font-family: 'BLUDHAVEN', sans-serif;
			font-size: 2em; 
		}

		#col2 {
			float: left; 
			width: 73%;
		}
		#col2 div{
			/*position: absolute;*/
			width: 60%;
			float: left;
			padding: 15%;
			padding-top: 20%;
			
		}
		#increaseFont {
			font-size: 2em;  
			color: #cf4230;
		}
		p {
			font-family: 'Raleway', sans-serif;
		}

		#col1 img {
			width: 15%;
			position: absolute;
			bottom: 1%;
		}
		
		#page3 {
			background-color: white;
			height: 100%;
		}
		#page3cont{
			width: 100%;
			height: 100%;
			padding-top: 5%;
			padding-bottom: 5%;
		}
		#goodTimes{
			border: 2px solid #fc8574/*e88476*/;
			width: 73%;
			margin: 0% auto;
			margin-bottom: 3%;
		}
		#page3 h2 {
			text-align: center;
			font-size:2em;
		}

		#pictures{
			margin-top: 100%;
			width:75%;
			height: 100%;
			margin: 0 auto;
		}
		#pictures iframe{
			width: 100%;
			height: 63%;
			border:none;
		}
		.page3circle {
   			position:absolute;
   			top: 0px;
   			right: 1%; 
   			height: 10%;
   			width: 10%;
   			transition: all 0.5s 0s;
   			text-align: right;
   			background-color: white;
   		}
   		.page3circle:hover {
   			border-radius: 0%;
   			bottom: 0px;
   			right: 15px; 
   			background-color: white; 
   			font-size: 1em; 
   			
   		}

   		.page3circle p {
   			font-family: "BLUDHAVEN";
   			color: #d15a4b;
   		}

   		.page3circle .menu {
   			opacity: 0;  
   			margin-top:-20px; 		
   		}
   		.page3circle:hover .menu {
   			opacity: 1;
   			transition: all 0.5s 0.3s;
   			transform:translateY(20px);

   		}

		#page4 {
			background-color: #f8f4f1;
			height: 100vh;
		}
		#page4 h2 {
			width:100%;  
			text-align: center;
			position: relative;
			top: 10vh;
			font-size:2em;
			padding: 0;
			margin: 0;
		}
		#p4col1 {
			width: 40%;
			height: 70%;
			border: 1px solid #d15a4b; 
			margin: auto;
			font-family: "Raleway", sans-serif;
			font-size: 105%;
			padding: 2%;
		}
		#p4col1 div{
			margin: 2%;
		}
		#colsContainer {
			margin-left: auto;
			margin-right: auto;
		}
		#colsContainer h3 {
			text-align: center; 
			font-family: "Raleway", sans-serif; 
			font-weight: 100; 
		}
		#colsContainer li { 
			font-family: "Raleway", sans-serif; 
			font-weight: 100; 
			font-size: 0.8em; 
			line-height: 150%; 
			margin-right: 10px; 
		}
		#page5{
			background-color: #ebd9d8;
			height: 100vh;
			overflow: hidden;
		}
		#page5 h2{
			padding-top: 47vh;
			text-align: right;
			font-size: 2em;
			margin-bottom: 5%;
			line-height: 5%;
			margin-right: 10%;
		}
		#whiteBox{
			width: 50%;
			height: 100%;
			background-color: white;
			float: left;
			font-family: 'Raleway';
			padding-top: 40vh;
		}
		#contactSimple{			
			width: 50%;
			float: left;
		}
		#whiteBox div{
			padding-left: 8%;
			margin: 3%;
			font-size: 120%;
		}
		#clearFloat{
			clear: both;
		}

	</style>
</head>
<body>
	<div id="container">
	<section id="page1">
		<div id='strike'></div>
		<div id="mainPicContainer">
			<img id="mainPic" src="img/jianigrad.jpg" alt="mainpic"> 
		</div>
		
		<h1 id='first'>JIANI</h1>
		<h1 id='last'>TIAN</h1>
		<div id="mainMenu">
			<a href="#page2">hbd</a>
			<a href="#page3">good times</a>
			<a href="#page4">gift</a>
			<a href="#page5">contact</a>
		</div>
	</section>



	<section id="page2">
		<div class="circleCont">
			<div class="page2circle">
				<p>menu</p>
				<div class="menu">
					<a href="#page2">hbd</a><br><br>
					<a href="#page3">good times</a><br><br>	
					<a href="#page4">gift</a><br><br>
					<a href="#page5">contact</a>
				</div>

			</div> <!-- circle -->
		</div> <!-- circle cont -->
		<div id="col1">
			<h2>HAPPY <br>BIRTHDAY</h2>
			<img src="img/quakeroats.png" alt="selfportrait">
		</div>
		
		<div id="col2">
			<div>
				<p id="increaseFont">Hello depepe!</p>
				<p>I was SOSOSO excited to be back for your college decisions, prom, and grad. Unfortunately, things didn't exactly go as we planned. Nevertheless, big things still continued to happen for you, and all I can say is you deserved every single thing. Whenever you told me about a new acceptance, I smiled so wide and literally jumped up and down. I can't express how proud I am. I'm glad these universities were able to see what we all saw in you. Your intelligence, compassion, ability to listen, sense of humor, music taste, and endless support for others are things thing I continue to be in awe of. Penn is so lucky you chose them, but I'm sad because it means you'll be all the way across the country (maybe I should have went to CMU huh JKJK). I've said it before, but I'm truly so lucky to have you in my life. I know you'll continue to do big things and I can't wait to see all that you accomplish. Happy birthday! I love you so much. </p>

				<p>GO QUAKERS!<br> ~depepe</p>
			</div>
		</div>

	</section>



	<section id="page3">
		<div id='page3cont'>
			<div id='goodTimes'>
				<h2>GOOD TIMES</h2>
			</div>
			<div class="circleCont">
				<div class="page3circle">
					<p>menu</p>
					<div class="menu">
						<a href="#page2">hbd</a><br><br>
						<a href="#page3">good times</a><br><br>	
						<a href="#page4">gift</a><br><br>
						<a href="#page5">contact</a>
					</div>

				</div> <!-- circle -->
			</div>
			<div id="pictures">
				<iframe name="my-frame" src="photo.html"></iframe>
			</div>
		</div>
	</section> 


	<div class="clearFloat"></div>


	<section id="page4">
		<h2>GIFT</h2>
		<div class="clearFloat"></div>
		<br><br><br><br><br><br><br><br><br>

		<div class="circleCont">
			<div class="page2circle">
				<p>menu</p>
				<div class="menu">
					<a href="#page2">hbd</a><br><br>
					<a href="#page3">good times</a><br><br>	
					<a href="#page4">gift</a><br><br>
					<a href="#page5">contact</a>
				</div>

			</div> <!-- circle -->
		


		</div> <!-- circle cont -->
		<div id="colsContainer">
			<div id="p4col1">
				<div>
					You're probably wondering why I made a website just to tell you things you alreay know or show you pictures I could have just posted on instagram. Well, to be honest, I always have trouble finding a gift for you. You literally have, or have the ability to buy, anything that you could possibly want as a gift. So, I decided to put my website making skills to use and build this for you.
				</div>
				<div>
					Right now it just has some basic sections, like an 'about' section, a section to showcase your art, and a 'contact' section. But, if you want to add anything else, just let me know! All the colors and layouts can change as well. I'm not the most 'designy' person so you're going to have to help me with that. 
				</div>
				<div>
					Anyway, I can't wait to hang out in person. Looking forward to our roadtrip for those fish tacos!
				</div>
				<div>
					- xoxo BICTH
				</div>
			</div>
		</div>

		<div></div>

	</section>
	<section>
		<div id='page5'>
			<div id='contactSimple'>
				<h2>CONTACT</h2>
			</div>
			<div id='whiteBox'>	
				<div>
					Email: <a href="mailto:someone@gmail.com">someone@gmail.com</a>
				</div>
				<div>
					Instagram <a href="https://www.instagram.com/jianitian/">@jianitian</a>
				</div>
				<div>
					LinkedIn: <a href="https://www.linkedin.com/in/jiani-tian-816784177">linkedin.com</a>
				</div>
			</div>
		</div>
	</section>
	</div> <!-- conatiner -->

	<!-- jquery -->
	<script src="https://code.jquery.com/jquery-3.4.1.min.js"
  integrity="sha256-CSXorXvZcTkaix6Yvo6HppcZGetbYMGWSFlBw8HfCJo="
  crossorigin="anonymous"></script>


  	<!-- smooth scroll -->
  		<script src="flowtype.js"></script>
	<script>
		//initialize smooth scroll 
		$('h1').flowtype({
		   fontRatio : 15
		});
		

		
	</script>



</body>
</html>
