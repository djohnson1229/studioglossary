<!DOCTYPE html>
<html>
<head>
	<title>HTML</title>

<style type="text/css">
	

/* 1.1. Base document elements
==================================== */

* {
	outline: none!important;
}
html {
	min-height: 100%;
	overflow-x: hidden;
}
body{margin: 0;font-family: 'Raleway', sans-serif;}
body.boxed, body.page-template-template-boxedpage-php {
	padding: 20px 0; }
.clearfix:after {
	content: ".";
	display: block;
	clear: both;
	visibility: hidden;
	line-height: 0;
	height: 0
}
/*.clearfix {
	display:inline-block
}*/

.onepcssgrid {
	margin: 0 auto;
	padding: 0;
	max-width: 1200px;
	position: relative
}

/* 4.3. Device classes
==================================== */

.onlyDesktop {
	display: block!important;
}
.onlyTablets {
	display: none!important;
}
.onlySmartphones {
	display: none!important;
}
.onlyTabltetsAndSmartphones {
	display: none!important;
}
/*
 *
------------------------------------ */
 
/* 6.2. Content layout style
==================================== */ 

/* Columns
---------------------------------------------------------- */
.onerow {
	clear: both;
	padding: 0 0px
}
.col1, .col2, .col3, .col4, .col5, .col6, .col7, .col8, .col9, .col10, .col11, .col12 {
	float: left;
	display: inline;
	margin-right: 2.127659574468%;
}
.col1.last, .col2.last, .col3.last, .col4.last, .col5.last, .col6.last, .col7.last, .col8.last, .col9.last, .col10.last, .col11.last, .col12 {
	margin: 0
}
.col1 {
	width: 6.382978723404%;
}
.col2 {
	width: 14.893617021277%;
}
.col3 {
	width: 23.4%;
}
.col4 {
	width: 31.914893617021%;
}
.col5 {
	width: 40.425531914894%;
}
.col6 {
	width: 48.936170212766%;
}
.col7 {
	width: 57.446808510638%;
}
.col8 {
	width: 65.957446808511%;
}
.col9 {
	width: 74.468085106383%;
}
.col10 {
	width: 82.978723404255%;
}
.col11 {
	width: 91.489361702128%;
}
.col12 {
	width: 100%;
	margin: 0
}
/*.col1 img, .col2 img, .col3 img, .col4 img, .col5 img, .col6 img, .col7 img, .col8 img, .col9 img, .col10 img, .col11 img, .col12 img {
	width:100%;
	height:auto;
	display:block
}*/
/* =Responsive Images
-------------------------------------------------------------- */
img {
	-ms-interpolation-mode: bicubic;
	border: 0;
	height: auto;
	max-width: 100%;
	vertical-align: middle;
}
.ie8 img {
	height: auto;
	width: auto\9;
}
.ie8 img.size-large {
	max-width: 60%;
	width: auto;
}
/* =Responsive Embeds/Objects
-------------------------------------------------------------- */
embed, object {
	max-width: 100%;
}
svg:not(:root) {
	overflow: hidden;
}
/* =Menu
-------------------------------------------------------------- */


/*========================================
			CONTENT START HERE
==========================================*/
/* 5.1. Main menu
==================================== */ 
.main-menu {
	background: url(../images/nav.jpg) 0 0 repeat-x;
	min-height: 43px;
}
nav {
	min-height: 43px;
	font-size: 14px;
	font-family: Tahoma;
	position: relative;
	font-weight: normal;
	font-weight: bold;
	float: left;
}
nav ul {
	padding: 0;
	margin: 0 auto;
}
nav li {
	  display: inline-block;
    position: relative;
}

nav li .submenu {
    background: #333 none repeat scroll 0 0;
    display: none;
    left: 0;
    position: absolute;
    top: 57px;
    width: 200px;
    z-index: 9;
}
nav li:hover .submenu{display: block;}
nav li:hover .submenu li{display: block;}

nav li:last-child {
	margin-right: 0;
}

nav li:hover{background: #7B9D52;}
nav li:hover a{color: #fff;}
nav li a.active:after {
	border-style: solid;
	border-width: 10px 9px 0;
	content: "";
	height: 0;
	left: 38%;
	position: absolute;
	top: 100%;
	width: 0;
}
nav li:last-child:after {
	background: none
}
nav a {
    color: #fff;
    display: inline-block;
    text-align: center;
    text-decoration: none;
    font-size: 20px;
    text-transform: uppercase;
    padding: 10px 10px;


}
li.addright {
    border-right: 1px solid #fff;
}
span.nextmenu {
    width: 12px;
    display: block;
    height: 12px;
    background: #000;
    border-radius: 100%;
    float: right;
    margin-left: 8px;
    margin-top: 8px;
}
.nextmenu.colorsection2 {
    background: #d04f54;
}
.nextmenu.colorsection4 {
    background: #fc9a2d;
}

.nextmenu.colorsection3 {
    background: #4767aa;
}

nav li a {
	box-sizing: border-box;
	-moz-box-sizing: border-box;
	-webkit-box-sizing: border-box;
}
nav li:last-child a {
	border-right: 0;
}
nav a:hover, nav a.active {
}
nav a#pull {
	display: none;
}



.about .col5 {
    padding: 4px;
}
 @media all and (max-width: 768px) {
.col1, .col2, .col3, .col4, .col5, .col6, .col7, .col8, .col9, .col10, .col11 {
	float: none;
	width: 99%;
	margin-right: 0;
	display: block;
	margin: 0 6px;
}
.fake-grid {
	display: none
}
body {
	font-size: 14px;
	line-height: 26px
}
.col1, .col2, .col3, .col4, .col5, .col6, .col7, .col8, .col9, .col10, .col11, .col12 {
	padding-top: 0px;
	padding-bottom: 0px
}
.col1, .col2, .col3, .col4, .col5, .col6, .col7, .col8, .col9, .col10, .col11, .col12 {
	float: none!important;
	margin: 0 auto 10px auto!important;
	max-width: 100%;
	width: 100%;
}
p {
	font-size: 13px;
	line-height: 20px;
	margin-bottom: 10px;
	color: #777;
}
.logo {
	text-align: center
}
nav {
	height: auto;
	float: none

}
nav ul {
	width: 100%;
	display: block;
	height: auto;
}
nav li {
	width: 100%;
	float: none;
	position: relative;
}
nav li a {
	border-bottom: 1px solid #ccc;
	/*border-right: 1px solid #576979;*/

	

	margin-right: 56px;
	width: 96%;
}
nav li a:hover {
	color: #333;
}
nav a {
	text-align: left;
	width: 100%;
	color: #333;
}

}

.backheader{background: url(images/banner.png) 0 0 no-repeat;background-size: cover;padding: 20px 0;}

.backheader h1{font-size: 150px; color: #000;  text-align: center;    font-weight: 800;}
.logo{margin-top: 20px;}
.about img{border-radius: 5px;}
.about h1{font-size: 20px; line-height: 28px; ;font-family: 'Raleway', sans-serif; font-weight: 700;}
.about p{font-size: 13px; line-height: 20px; ;font-family: 'Raleway', sans-serif; font-weight: 400;}

.themenav li {
    display: inline-block;
    list-style: outside none none;
    padding: 0 10px;
}
.themenav{
  text-align: right;
}

.border{/*border-bottom:1px solid #999; */  margin-bottom: 40px;
    padding-bottom: 40px;}
.roundlogo{  background: #d04f54 none repeat scroll 0 0;
    border-radius: 100%;
    display: inline-block;
    height: 40px;
    vertical-align: middle;
    width: 40px; margin-bottom: 7px;}

.womenslogo {
    color: #000;
    font-size: 50px;
    text-decoration: none;
    text-transform: uppercase; font-weight: 700;
}

.themenav a{color: #333; text-decoration: none;}
.themenav a:hover,.themenav a:focus{color: #D04F54;     border-bottom: 1px solid;}

.onerow.navthem {
    border-bottom: 1px solid #999;
    margin-bottom: 40px;
    padding-bottom: 72px;
}

.headernav {
    background: #88B265 none repeat scroll 0 0; margin: 0 0 30px;
}
.theme1{text-align: center; padding-top: 50px;}

.section2 .col6 {
    margin-bottom: 11px;
    width: 48.9362%;
}
.section3 .col6 {
    margin-bottom: 11px;
    width: 48.9362%;
}

.section4 .col6 {
    margin-bottom: 11px;
    width: 48.9362%;
}
.floatright {float:right;}

.theme2 h1,.theme2 p{text-align: center;}
.theme2 {
    padding-top: 30px;
}
  .section2 .col6, .section3 .col6, .section4 .col6{position: relative;}

   .section2 .col6 .borderright,.section3 .col6 .borderright ,.section4 .col6 .borderright  {
    border: 1px solid #999;
    height: 100%;
    position: absolute;
    right: -12px;}
.section3 {
    padding-top: 50px;
}


.roundlogokids{  background: #fc9a2d none repeat scroll 0 0;
    border-radius: 100%;
    display: inline-block;
    height: 40px;
    vertical-align: middle;
    width: 40px; margin-bottom: 7px;}

.roundlogoH{  background: #4767aa none repeat scroll 0 0;
    border-radius: 100%;
    display: inline-block;
    height: 40px;
    vertical-align: middle;
    width: 40px; margin-bottom: 7px;}


.section4{
    padding-top: 50px;
}


.footer {
    background: #333 none repeat scroll 0 0;
    color: #fff;
    margin-top: 60px;
    padding: 30px 0;
    text-align: center;
}
.scrollside {
    position: fixed;
    right: 0;
    top: 35%;   z-index: 9;
}

.scrollside li {
    background: #ccc;
    border-radius: 100%;
    display: block;
    height: 30px;
    margin: 10px;
    width: 30px; cursor: pointer;
    margin: 6px auto;
}

.scrollside .colorsection2{
    background: #d04f54;
}
.scrollside .colorsection3{
    background: #fc9a2d ;
}
.scrollside .colorsection4{
    background: #4767aa ;
}
.scrollside li.active {
    height: 38px; 
    width: 38px; 
}





 @media screen and (max-width: 1200px) {
.onepcssgrid{
	padding: 0 20px;
}
}
 @media all and (max-width: 800px) {
.section2 .col6 .borderright, .section3 .col6 .borderright, .section4 .col6 .borderright{display: none !important;}

nav a#pull {
    display: block;
}

nav li a {
    color: #000;
}


nav a#pull::after {
    background: rgba(0, 0, 0, 0) url("nav-icon.png") no-repeat scroll 0 0;
    content: "";
    display: inline-block;
    height: 30px;
    position: absolute;
    right: 15px;
    top: 10px;
    width: 30px;
}
nav a#pull {
    background-color: #4767aa;
    color: #ffffff;
    display: block;
    margin-left: 0;
    margin-right: 0;
    margin-top: 0;
    padding: 10px 0;
    position: relative;
    text-indent: 15px;
    width: 100%;
}

nav li a:hover {
    color: #fff;
}

nav ul {
    display: none;
 }
.backheader h1 {
   
    font-size: 50px;

}

.col6{width: 100% !important;}

.themenav {
    text-align: center;
}

.themenav li {
    border-bottom: 1px solid #999;
    display: block;
    list-style: outside none none;
    padding: 10px;
}

.themenav {
    margin: 0;
    padding: 0;
    text-align: center;
}

}


ul.newlisting {
    padding: 0 18px;
}

.newlisting li {
    margin: 10px 0;
}

.heightcheck .col4 img {
    max-height: 190px;
}

.imagessame img {
    max-height: 383px;
}
.heightcheck1 .col4 img {
    max-height: 225px;
}

.col6 img {
    max-height: 190px;
    width: 100%;
}

</style>
<link href="https://fonts.googleapis.com/css?family=Raleway:100,100i,200,200i,300,300i,400,400i,500,500i,600,600i,700,700i,800,800i,900,900i" rel="stylesheet"> 

<script src="jq.js"></script>
<script src="jquery.waypoints.min.js"></script>

<script>

	$(function() {

		var pull 		= $('#pull');

			menu 		= $('nav ul:first-child');

			menuHeight	= menu.height();

		$(pull).on('click', function(e) {

			e.preventDefault();

			menu.slideToggle();

		});

       	$(window).resize(function(){

			var w = $(window).width();

			if(w > 800 && menu.is(':hidden')) {

				$('nav ul').removeAttr('style');

			}

		});

	});

</script>




</head>
<body>
<ul class="scrollside">
	<li class="colorsection2 scrolltodiv" todiv ="section2"></li>
	<li class="colorsection3 scrolltodiv" todiv ="section4"></li>
	<li class="colorsection4 scrolltodiv" todiv ="section3"></li>
</ul>

<div id ="section1" class="section1">

	<!--div class="backheader">
	<div class="clearfix onepcssgrid">
   <a href="#" class="logo"><img style="visibility:hidden;" src="logo.png" alt="logo"></a>
   <h1>	Welcome</h1>

	</div>
	</div-->
	<div class="clearfix headernav">
		<div class="onepcssgrid">
<nav class="navigation" id="nav">
  
	<ul>
		<li class="addright">   <a class="scrolltodiv" todiv ="section2" href="#">Womens<span class="colorsection2 nextmenu"></span></a>	</li>
		<li class="addright">  <a class="scrolltodiv" todiv ="section4" href="#">Kids<span class="colorsection4 nextmenu"></a>		</li>
		<li>  <a class="scrolltodiv" todiv ="section3" href="#">Home and Hardlines<span class="colorsection3 nextmenu"></a></li>
	</ul>
  <a href="#" id="pull">Menu</a> 
</nav>
</div>
</div>

	<div class="clearfix border onepcssgrid">
		



<div class="onerow about">
	<div class="col5">
<h1>About This Glossary: </h1>

<p>
Thank you for visiting the Studio Glossary. This is the place where we can bridge the context gap between Merch and Studio. We hope this feature has beneficial uses for you in your org! </p>
<!--p>
<strong>Have any feedback or questions?</strong> <br/><br/>

<strong>Contact: abcdef@gmail.com</strong> <br/>
 </p-->
</div><div class="col3"></div>
	<div class="col5 last floatright">

<img src="images/aboutm.jpg" alt="about">
</div>

</div>

	</div>


</div>

<section id ="section2" class="section2">
	<div class="clearfix womensec onepcssgrid">
	<div class="onerow navthem">
			<div class="col3"> <a href="#" class="womenslogo">Women <span class="roundlogo"></span></a></div>
            <div class="col9 last">
        <ul class="themenav">
		<li>   <a href="#"class="scrolltodiv" todiv ="section2theme1" >Boho</a></li>
		<li>  <a href="#" class="scrolltodiv" todiv ="section2theme2">Modern</a></li>
		<li>  <a href="#" class="scrolltodiv" todiv ="section2theme3">Blogger Style</a></li>
		<li>  <a href="#" class="scrolltodiv" todiv ="section2theme4">Western</a></li>
		<li>  <a href="#" class="scrolltodiv" todiv ="section2theme5">Preppy</a></li>
		<li>  <a href="#" class="scrolltodiv" todiv ="section2theme6">Nautical</a></li>
		<li>  <a href="#" class="scrolltodiv" todiv ="section2theme7">Shabby Chic</a></li>
		<li>  <a href="#" class="scrolltodiv" todiv ="section2theme8">Feminine / Romantic</a></li>

	    </ul>

            </div>

          </div>

<div class="onerow about">
	<div class="col5">
<h1>About</h1>

<p>
There are several categories that are frequently requested within the Women’s department:
<ul class="newlisting">
 	<li><b>Boho</b><b>
</b></li>
 	<li><b>Modern
</b></li>
 	<li><b>Blogger Style </b></li>
 	<li><b>Western</b><b>
</b></li>
 	<li><b>Preppy
</b></li>
 	<li><b>Nautical</b></li>
 	<li><b>Shabby Chic</b><b>
</b></li>
 	<li><b>Feminine / Romantic</b></li>
</ul></p>
<!--p>
<strong>Have any feedback or questions?</strong> <br/><br/>

<strong>Contact: abcdef@gmail.com</strong> <br/>
 </p-->
</div>

 <div class="col5 last floatright"><img src="images/Picture3.jpg" alt="about">

    </div>
 

</div>

	</div>


</div>




<div class="clearfix theme1 onepcssgrid">
<h1 id="section2theme1">Boho</h1>
<p>Boho Definition: Style drawing from bohemian and hippie influences with a gypsy, folky element. Accessories might include: over-accessorizing with bangles, scarves, layered long necklaces, hats, rings, long vests. Possible HMU: braids, tousled waves, smoky eye, highlighter.

<u>Brand Reference: Free People, Anthropologie</u></p>

<div class="onerow">
	<div class="col4">

<img src="images/Picture5.jpg" alt="about">
</div>
	<div class="col4">

<img src="images/Picture6.jpg" alt="about">
</div>


	<div class="col4 last">

<img src="images/Picture7.jpg" alt="about">
</div>


</div>

</div>



<div class="clearfix theme2 onepcssgrid">


	<div class="col6">
	<div class="borderright"></div>
<p><h1 id="section2theme2">Modern</h1>
Modern Definition: Simple, clean lines, minimal; possibly structured, oversized or geometric.
Possible HMU: sleek, straight hair,  strong brows, possible statement lip or eye, clean makeup.
</br><u>Brand Reference: Aritzia, Totokaeio, Eileen Fisher, The Row</u></br></br></p>

<div class="onerow">

	<div class="col4">

<img src="images/Picture5.jpg" alt="about">
</div>
	<div class="col4">

<img src="images/Picture6.jpg" alt="about">
</div>


	<div class="col4 last">

<img src="images/Picture7.jpg" alt="about">
</div>

</div>


</div>


<div class="col6 last">


<p><h1 id="section2theme3">Blogger Style</h1>
Blogger Style Definition: Street style, trendy, girl on the go, playfully accessorized (including hats, sunnies, etc.), with a coffee or cell phone in hand. Possible HMU: tousled waves, subtle contouring and highlighting, trendy makeup. </br>
<u>Brand Reference: fast fashion including F21, Zara, Asos, Nasty Gal. Target, etc. </u>
</p>

<div class="onerow">

<div class="col4">

<img src="images/Picture8.jpg" alt="about">
</div>
	<div class="col4">

<img src="images/Picture9.jpg" alt="about">
</div>


	<div class="col4 last">

<img src="images/Picture10.jpg" alt="about">
</div>	

</div>


</div>



</div>




<div class="clearfix theme1 onepcssgrid">
<h1 id="section2theme4">Western</h1>
<p>Western Definition: Cowboy-inspired, classic styles, Canadian tuxedo. Accessories and elements may include paisley, scarf neck-tie, cowboy hat, leather boots, tassels. Possible HMU: clean face, hair with volume and curls. 
<br/><u>Brand Reference: Wrangler, Sundance, Ralph Lauren</u>
 </p>

<div class="onerow">
	<div class="col4">

<img src="images/Picture11.jpg" alt="about">
</div>
	<div class="col4">

<img src="images/Picture12.jpg" alt="about">
</div>
	<div class="col4 last">

<img src="images/Picture13.jpg" alt="about">
</div>



</div>

</div>



<div class="clearfix theme2 onepcssgrid">

	<div class="col6">
	<div class="borderright"></div>
<p><h1 id="section2theme5">Nautical</h1>
Nautical Definition: Vertical blue and white stripes with red accents with a preppy, All American feel; may include khaki, cardigans, denim, flats, boat shoes, hats, double breasted peacoat. Possible HMU: Red lip, cat eye, flawless skin. </br>
<u>Brand Reference: Nautica, J. Crew, Sperry, Ralph Lauren</u></p>

<div class="onerow">

	<div class="col4">

<img src="images/Picture14.jpg" alt="about">
</div>
<div class="col4">

<img src="images/Picture15.jpg" alt="about">
</div>

<div class="col4 last">

<img src="images/Picture16.jpg" alt="about">
</div>

</div>


</div>


<div class="col6 last">

<p><h1 id="section2theme6">Preppy</h1>
Preppy Definition: Tailored, polished, tucked in, high-waisted skirts and trousers, chinos, pleated skirts, sweaters layered over collared shirts, refined jewelry, penny loafers and boat shoes, with a nod towards the uniform and equestrian. Possible HMU: glowing skin, headbands, ponytails, side part.  <br/>
<u>Brand Reference Kate Spade, J. Crew, Tommy Hilfiger, Ted Baker </u></p>

<div class="onerow">

	<div class="col4">

<img src="images/Picture17.jpg" alt="about">
</div>

<div class="col4">

<img src="images/Picture18.jpg" alt="about">
</div>

	<div class="col4 last">

<img src="images/Picture19.jpg" alt="about">
</div>

</div>


</div>



</div>

<div class="clearfix theme2 onepcssgrid">

	<div class="col6">
	<div class="borderright"></div>
<p><h1 id="section2theme7">Shabby Chic</h1>
Shabby Chic Definition: Vintage, feminine, neutrals and pastels, English rose garden, lace, often loose fitting on the body. Weathered, white washed wood, white brick. Possible HMU: Soft curls, messy side bun.

</br>
<u>Brand Reference Anthropologie, Pretty Angel </u></p>

<div class="onerow">

	<div class="col4">

<img src="images/Picture20.jpg" alt="about">
</div>
<div class="col4">

<img src="images/Picture21.jpg" alt="about">
</div>

<div class="col4 last">

<img src="images/Picture22.jpg" alt="about">
</div>

</div>


</div>


<div class="col6 last">

<p><h1 id="section2theme8">Feminine / Romantic</h1>
Feminine / Romantic Definition: Softer, pinks, white, laces, chiffon, delicate details, flowy. Possible HMU: Wavy and curly hair, loose braids, flushed cheeks, stained lips. 
<br/>
<u>Brand Reference: For Love and Lemons, Lauren Conrad, Blush, Ralph Lauren</u></p>

<div class="onerow">

	<div class="col4">

<img src="images/Picture23.jpg" alt="about">
</div>

<div class="col4">

<img src="images/Picture24.jpg" alt="about">
</div>

	<div class="col4 last">

<img src="images/Picture25.jpg" alt="about">
</div>

</div>


</div>

</div>


</section>


<section id ="section4" class="section4">
	<div class="clearfix womensec onepcssgrid">
	<div class="onerow navthem">
			<div class="col3"> <a href="#" class="womenslogo">KIDS <span class="roundlogokids"></span></a></div>
            <div class="col9 last">
        <ul class="themenav">
		<li>   <a href="#"class="scrolltodiv" todiv ="section4theme1" >Preppy</a></li>
		<li>  <a href="#" class="scrolltodiv" todiv ="section4theme2">TRENDY</a></li>
		<li>  <a href="#" class="scrolltodiv" todiv ="section4theme3">BOHO</a></li>
		<li>  <a href="#" class="scrolltodiv" todiv ="section4theme4">COOL KID</a></li>
		<li>  <a href="#" class="scrolltodiv" todiv ="section4theme5">Traditional</a></li>
		<li>  <a href="#" class="scrolltodiv" todiv ="section4theme6">Vintage</a></li>
		<li>  <a href="#" class="scrolltodiv" todiv ="section4theme7">Nautical</a></li>
		<li>  <a href="#" class="scrolltodiv" todiv ="section4theme8">Surfer</a></li>
		<li>  <a href="#" class="scrolltodiv" todiv ="section4theme9">Playful</a></li>
		<li>  <a href="#" class="scrolltodiv" todiv ="section4theme10">Whimsical</a></li>
	    </ul>

            </div>

          </div>

<div class="onerow about">
	<div class="col5">
<h1>About </h1>

<p>
These are the several Categories that are frequently asked about within the kids Division. 
<ul class="newlisting">
 	<li><b>Preppy</b><b>
</b></li>
 	<li><b>TRENDY
</b></li>
 	<li><b>BOHO</b></li>
 	<li><b>COOL KID</b><b>
</b></li>
 	<li><b>Traditional
</b></li>
 	<li><b>Vintage</b></li>
 	<li><b>Nautical</b><b>
</b></li>
 	<li><b>Surfer</b></li>
<li><b>Playful</b></li>
<li><b>Whimsical</b></li>
</ul></p>

<!--strong>Have any feedback or questions?</strong> <br/><br/>

<strong>Contact: abcdef@gmail.com</strong> <br/> </p-->
</div><div class="col3"></div>
	<div class="col5 last floatright">

<img src="images/aboutkid.jpg" alt="about">
</div>

</div>

	</div>



<div class="clearfix theme1 onepcssgrid">
<h1 id="section4theme1">Preppy</h1>
<p>Stylish, classic</p>

<div class="onerow">
	<div class="col3">

<img src="images/Picture26.jpg" alt="about">
</div>
	<div class="col3">

<img src="images/Picture27.jpg" alt="about">
</div>
	<div class="col3">

<img src="images/Picture28.jpg" alt="about">
</div>

	<div class="col3 last">

<img src="images/Picture29.jpg" alt="about">
</div>


</div>

</div>



<div class="clearfix theme2 onepcssgrid">


	<div class="col6">
	<div class="borderright"></div>
<p><h1 id="section4theme2">TRENDY</h1>Aspirational, fun, fashionable</p>

<div class="onerow">

	<div class="col6">

<img src="images/Picture30.jpg" alt="about">
</div>
	<div class="col6 last">

<img src="images/Picture31.jpg" alt="about">
</div></div>
<div class="onerow">
	<div class="col6">

<img src="images/Picture32.jpg" alt="about">
</div>

	<div class="col6 last">

<img src="images/Picture33.jpg" alt="about">
</div>
</div>


</div>


<div class="col6 last">


<p><h1 id="section4theme3">BOHO</h1> Modern, trendy, hippy chic
</p>

<div class="onerow">

	<div class="col6">

<img src="images/Picture34.jpg" alt="about">
</div>
	<div class="col6 last">

<img src="images/Picture35.jpg" alt="about">
</div></div>
<div class="onerow">
	<div class="col6">

<img src="images/Picture36.jpg" alt="about">
</div>

	<div class="col6 last">

<img src="images/Picture37.jpg" alt="about">
</div>
</div>


</div>



</div>




<div class="clearfix theme1 onepcssgrid">
<h1 id="section4theme4">COOL KID</h1> Urban, attitude, fashion 
</p>

<div class="onerow">
	<div class="col3">

<img src="images/Picture38.jpg" alt="about">
</div>
	<div class="col3">

<img src="images/Picture39.jpg" alt="about">
</div>
	<div class="col3">

<img src="images/Picture40.jpg" alt="about">
</div>

	<div class="col3 last">

<img src="images/Picture41.jpg" alt="about">
</div>


</div>

</div>



<div class="clearfix theme2 onepcssgrid">

	<div class="col6">
	<div class="borderright"></div>
<p><h1 id="section4theme5">Traditional</h1> Conservative, Classic
</p>

<div class="onerow">

	<div class="col6">

<img src="images/Picture42.jpg" alt="about">
</div>
	<div class="col6 last">

<img src="images/Picture43.jpg" alt="about">
</div></div>
<div class="onerow">
	<div class="col6">

<img src="images/Picture44.jpg" alt="about">
</div>

	<div class="col6 last">

<img src="images/Picture45.jpg" alt="about">
</div>
</div>


</div>


<div class="col6 last">

<p><h1 id="section4theme6">Vintage</h1>Fashionable shabby chic
</p>

<div class="onerow">

	<div class="col6">

<img src="images/Picture46.jpg" alt="about">
</div>
	<div class="col6 last">

<img src="images/Picture47.jpg" alt="about">
</div></div>
<div class="onerow">
	<div class="col6">

<img src="images/Picture48.jpg" alt="about">
</div>

	<div class="col6 last">

<img src="images/Picture49.jpg" alt="about">
</div>
</div>


</div>



</div>


<div class="clearfix theme1 onepcssgrid">
<h1 id="section4theme7">Nautical</h1>Summer east coast, preppy beach, traditional, backyard 
 
</p>

<div class="onerow">
	<div class="col3">

<img src="images/Picture50.jpg" alt="about">
</div>
	<div class="col3">

<img src="images/Picture51.jpg" alt="about">
</div>
	<div class="col3">

<img src="images/Picture52.png" alt="about">
</div>

	<div class="col3 last">

<img src="images/Picture53.jpg" alt="about">
</div>


</div>

</div>



<div class="clearfix theme2 onepcssgrid">

	<div class="col6">
	<div class="borderright"></div>
<p><h1 id="section4theme8">Surfer</h1>Summer west coast, casual L.A. trendy, tropical 

</p>

<div class="onerow">

	<div class="col6">

<img src="images/Picture54.jpg" alt="about">
</div>
	<div class="col6 last">

<img src="images/Picture55.jpg" alt="about">
</div></div>
<div class="onerow">
	<div class="col6">

<img src="images/Picture56.jpg" alt="about">
</div>

	<div class="col6 last">

<img src="images/Picture57.jpg" alt="about">
</div>
</div>


</div>


<div class="col6 last">

<p><h1 id="section4theme9">Playfu</h1>- Fun, active, emotion
</p>

<div class="onerow">

	<div class="col6">

<img src="images/Picture58.jpg" alt="about">
</div>
	<div class="col6 last">

<img src="images/Picture59.jpg" alt="about">
</div></div>
<div class="onerow">
	<div class="col6">

<img src="images/Picture60.jpg" alt="about">
</div>

	<div class="col6 last">

<img src="images/Picture61.jpg" alt="about">
</div>
</div>


</div>



</div>

<div class="clearfix theme1 onepcssgrid">
<h1 id="section4theme10">Whimsical</h1>  Fantasy, imagination, surreal
 
</p>

<div class="onerow">
	<div class="col3">

<img src="images/Picture62.jpg" alt="about">
</div>
	<div class="col3">

<img src="images/Picture63.jpg" alt="about">
</div>
	<div class="col3">

<img src="images/Picture64.jpg" alt="about">
</div>

	<div class="col3 last">

<img src="images/Picture65.jpg" alt="about">
</div>


</div>

</div>


</section>


<section id="section3" class="section3">
	<div class="clearfix womensec onepcssgrid">
	<div class="onerow navthem">
			<div class="col3"> <a href="#" class="womenslogo">H&HL <span class="roundlogoH"></span></a></div>
            <div class="col9 last">
        <ul class="themenav">
		<li>   <a href="#"class="scrolltodiv" todiv ="section3theme1" >Cabin</a></li>
		<li>  <a href="#" class="scrolltodiv" todiv ="section3theme2">Coastal/Nautical</a></li>
		<li>  <a href="#" class="scrolltodiv" todiv ="section3theme3">Farm House</a></li>
		<li>  <a href="#" class="scrolltodiv" todiv ="section3theme4">Industrial</a></li>
		<li>  <a href="#" class="scrolltodiv" todiv ="section3theme5">Modern</a></li>
		<li>  <a href="#" class="scrolltodiv" todiv ="section3theme6">Rutisc</a></li>
		<li>  <a href="#" class="scrolltodiv" todiv ="section3theme7">Shabby Chic</a></li>
		<li>  <a href="#" class="scrolltodiv" todiv ="section3theme8">Vintage</a></li>

	    </ul>

            </div>

          </div>

<div class="onerow about">
	<div class="col5">
<h1>About </h1>


<p>
These are the several Categories that are frequently asked about within the Home and Hardlines Division.
 
<ul class="newlisting">
 	<li><b>Cabin</b></li>
 	<li><b>Coastal/Nautical
</b></li>
 	<li><b>Farm House
</b></li>
 	<li><b>Industrial
</b></li>
 	<li><b>Modern
</b></li>
 	<li><b>Rutisc</b></li>
 	<li><b>Shabby Chic
</b></li>
 	<li><b>Vintage</b></li>
</ul>
</p>
<!--p>
<strong>Have any feedback or questions?</strong> <br/><br/>

<strong>Contact: abcdef@gmail.com</strong> <br/></p-->
</div>
	<div class="col5 last floatright">

		<img src="images/abouthome.jpg" alt="about">

</div>

</div>

	</div>



<div class="clearfix theme1 onepcssgrid newheightcheck">
<h1 id="section3theme1">Cabin</h1>
<p>Elements taken from cabins or cottages. Dark woods, leather, plaid, outdoors, pategonia</p>

<div class="onerow imagessame">
	<div class="col4">

		<img src="images/Picture70.jpg" alt="about">
</div>
	<div class="col4">

		<img src="images/Picture71.jpg" alt="about">
</div>
	

	<div class="col4 last">

		<img src="images/Picture72.jpg" alt="about">
</div>


</div>

</div>



<div class="clearfix theme2 onepcssgrid heightcheck">


	<div class="col6">
	<div class="borderright"></div>
<p><h1 id="section3theme2">Coastal/Nautical</h1>
rugged, natural beauty. nature-inspired textures, earthy colors, organic warmth.</p>

<div class="onerow">

	<div class="col4">

		<img src="images/Picture73.jpg" alt="about">
</div>
	<div class="col4">

		<img src="images/Picture74.jpg" alt="about">
</div>

<div class="col4 last">

		<img src="images/Picture75.jpg" alt="about">
</div>

</div>


</div>


<div class="col6 last">


<p><h1 id="section3theme3">Farm House</h1>
 Repurosed, white washed wood, reclaimed wood, lighter colors, Americana.
</p>

<div class="onerow">

	<div class="col6">

		<img src="images/Picture76.jpg" alt="about">
</div>
	<div class="col6 last">

		<img src="images/Picture77.jpg" alt="about">
</div></div>

</div>



</div>




<div class="clearfix theme1 onepcssgrid newheightcheck">
<h1 id="section3theme4">Industrial</h1>
<p>Metal, raw materials, woods, concrete, loft style. This  style refers to an aesthetic trend in interior design that takes clues from old factories and industrial spaces that in recent years have been converted to lofts and other living spaces. ... Industrial style can also be seen in the use of unexpected materials used in building.</p>

<div class="onerow imagessame">
	<div class="col4">

		<img src="images/Picture78.jpg" alt="about">
</div>
	<div class="col4">

		<img src="images/Picture79.jpg" alt="about">
</div>
	<div class="col4 last">

		<img src="images/Picture80.jpg" alt="about">
</div>


</div>

</div>



<div class="clearfix theme2 onepcssgrid heightcheck">

	<div class="col6">
	<div class="borderright"></div>
<p><h1 id="section3theme5">Modern</h1>
Clean lines with a casual atmosphere, open spaces, neutral colors, and elements and materials inspired by nature.</p>

<div class="onerow">

	<div class="col4">

		<img src="images/Picture81.jpg" alt="about">
</div>
	<div class="col4">

		<img src="images/Picture82.jpg" alt="about">
</div>
	<div class="col4 last">

		<img src="images/Picture83.jpg" alt="about">
</div>
</div>


</div>


<div class="col6 last">

<p><h1 id="section3theme6">Rutisc</h1>
emphasis on rugged, natural beauty. It embraces nature-inspired textures, simple and earthy colors, and ultimately an unpretentious, organic warmth.</p>
<div class="onerow">

	<div class="col4">

		<img src="images/Picture84.jpg" alt="about">
</div>
	<div class="col4 ">

		<img src="images/Picture85.jpg" alt="about">
</div>
	<div class="col4 last ">

		<img src="images/Picture86.jpg" alt="about">
</div>
</div>


</div>



</div>


<div class="clearfix theme2 onepcssgrid heightcheck1">

	<div class="col6">
	<div class="borderright"></div>
<p><h1 id="section3theme7">Shabby Chic</h1>
furnishings are either chosen for their appearance of age and signs of wear and tear or where new items are distressed to achieve the appearance of an antique.</p>

<div class="onerow">

	<div class="col6">

		<img src="images/Picture87.jpg" alt="about">
</div>
	
	<div class="col6 last">

		<img src="images/Picture88.jpg" alt="about">
</div>
</div>


</div>


<div class="col6 last">

<p><h1 id="section3theme8">Vintage</h1>
General trends between the 50-70’s. </p>
<div class="onerow">

	<div class="col4">

		<img src="images/Picture89.jpg" alt="about">
</div>
	<div class="col4 ">

		<img src="images/Picture90.jpg" alt="about">
</div>
	<div class="col4 last ">

		<img src="images/Picture91.jpg" alt="about">
</div>
</div>


</div>



</div>

</section>

<div class="footer">
	

<div class="onepcssgrid"> All Right Reserved.  </div>

</div>


<script>

var waypoint = new Waypoint({
  element: document.getElementById('section2'),
  handler: function(direction) {
jQuery('.scrollside li').removeClass('active');
jQuery('.scrollside li.colorsection2').addClass('active');

  }
})

var waypoint1 = new Waypoint({
  element: document.getElementById('section3'),
  handler: function(direction) {
jQuery('.scrollside li').removeClass('active');
jQuery('.scrollside li.colorsection4').addClass('active');
  }
})

var waypoint2 = new Waypoint({
  element: document.getElementById('section4'),
  handler: function(direction) {
jQuery('.scrollside li').removeClass('active');
jQuery('.scrollside li.colorsection3').addClass('active');
  }
})

var waypoint3 = new Waypoint({
  element: document.getElementById('section1'),
  handler: function(direction) {
jQuery('.scrollside li').removeClass('active');
  }
})
var waypoint4 = new Waypoint({
  element: document.getElementById('nav'),
  handler: function(direction) {
jQuery('.scrollside li').removeClass('active');
  }
})


$(".scrolltodiv").click(function(e) {
e.preventDefault();
   
if($(this).attr('todiv') == "section2")
{
$('body').animate({
        scrollTop: eval($('#' + $(this).attr('todiv')).offset().top - 40)
    }, 1000);

}
else
{
$('body').animate({
        scrollTop: eval($('#' + $(this).attr('todiv')).offset().top)
    }, 1000);


}
});

</script>



</body>
</html>

