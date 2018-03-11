@charset "UTF-8";
/* Body */
body {
	font-family: source-sans-pro;
	background-color: #f2f2f2;
	margin-top: 0px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
	font-style: normal;
	font-weight: 200;
}


/* Container */
.container {
	width: 100%;
	margin-left: auto;
	margin-right: auto;
	height: 1000px;
	background-color: #FFFFFF;
}
/* Navigation */
header {
	width: 100%;
	height: 5%;
	background-color: #111213;
	border-bottom: 1px solid #FFFF;
	
}

#logox{  
width: 50px;
height: 49px;
float: left;
margin-left: 10px;
	overflow: hidden;
	}

.logo {
	color: #fff;
	font-weight: bold;
	text-align: undefined;
	width: 30%;
	float: left;
	margin-top: 15px;
	margin-left: 25px;
	letter-spacing: 4px;
}

nav {
	float: right;
	width: 50%;
	text-align: right;
	margin-right: 25px;
}
header nav ul {
	list-style: none;
	float: right;
}
nav ul li {
	float: left;
	color: #FFFFFF;
	font-size: 14px;
	text-align: left;
	margin-right: 25px;
	letter-spacing: 2px;
	font-weight: bold;
	transition: all 0.3s linear;
}
ul li a {
	color: #FFFFFF;
	text-decoration: none;
}
ul li:hover a {
	color: #000000;
}
.hero_header {

	text-align: center;
	margin-top: 70px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
	letter-spacing: 4px;
	font-size: 2em;
    z-index: 0;
	float: none;
    color: #fff;
    line-height: 65px;
    text-align: center;
    text-transform: uppercase;
	font-family: "Montserrat", Helvetica, sans-serif;
    font-weight: 700;
    line-height: 40px;
}


/* Hero Section */
.hero {
	
	padding-bottom: 7px;
	background-image: url(https://i.imgur.com/BKktXZo.png) ;
	background-repeat: no-repeat;
	background-size: cover;
	background-position: center;
	height: 26%;
	width: 100%;
}



.title {
	
	font-size: 40px;
	text-align: center;
	border-color: white;
	color: white;
	padding-bottom: 0px;
}
.light {
	font-weight: bold;
	color: #717070;
}
.tagline {
	text-align: center;
	color: #FFFFFF;
	margin-top: 4px;
	font-weight: lighter;
	text-transform: uppercase;
	letter-spacing: 1px;
	font-weight: 690;
	font-size: 12px;
	font-family: Cambria, "Hoefler Text", "Liberation Serif", Times, "Times New Roman", "serif";
	}
/* About Section */
.text_column {
	width: 28%;
	text-align: justify;
	font-weight: lighter;
	line-height: 25px;
	float: left;
	padding-left: 20px;
	padding-right: 20px;
	color: #ffffcc;
	margin-left: 10px;
	}
.about {
	padding-left: 25px;
	padding-right: 25px;
	display: inline-block;
	background: #050505;
	margin-top: 0px;
	
}

.thumbnail {
	width: 25%;
	text-align: center;
	float: left;
	margin-top: 35px;
}
.gallery .thumbnail h4 {
	margin-top: 5px;
	margin-right: 5px;
	margin-bottom: 5px;
	margin-left: 5px;
	color: #52BAD5;
}
.gallery .thumbnail p {
	margin-top: 0px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
	color: #A3A3A3;
}
/* Parallax Section */
.banner {
	background-image: url(file:///C|/Users/Madson/AppData/Roaming/Adobe/Dreamweaver%20CC%202017/pt_BR/Configuration/Temp/images/parallax.png);
	height: 400px;
	background-attachment: fixed;
	background-size: cover;
	background-repeat: no-repeat;
}
.parallax {
	color: #FFFFFF;
	text-align: right;
	padding-right: 100px;
	padding-top: 110px;
	letter-spacing: 2px;
	margin-top: 0px;
}
.parallax_description {
	color: #FFFFFF;
	text-align: right;
	padding-right: 100px;
	width: 30%;
	float: right;
	font-weight: lighter;
	line-height: 23px;
	margin-top: 0px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
}
/* More info */
footer {
	background-color: #FFFFFF;
	padding-bottom: 35px;
}
.footer_column {
	width: 50%;
	text-align: center;
	padding-top: 30px;
	float: left;
}
footer .footer_column h3 {
	color: #B3B3B3;
	text-align: center;
}
footer .footer_column p {
	color: #717070;
	background-color: #FFFFFF;
}
.cards {
	width: 100%;
	height: auto;
	max-width: 400px;
	max-height: 200px;
}
footer .footer_column p {
	padding-left: 30px;
	padding-right: 30px;
	text-align: justify;
	line-height: 25px;
	font-weight: lighter;
	margin-left: 20px;
	margin-right: 20px;
}
.button {
	width: 200px;
	margin-top: 40px;
	margin-right: auto;
	margin-bottom: auto;
	margin-left: auto;
	padding-top: 20px;
	padding-right: 10px;
	padding-bottom: 20px;
	padding-left: 10px;
	text-align: center;
	vertical-align: middle;
	border-radius: 0px;
	text-transform: uppercase;
	font-weight: bold;
	letter-spacing: 2px;
	border: 1px solid #FFFFFF;
	color: #FFFFFF;
	transition: all 0.3s linear;
	text-decoration: none;
	display: block;
}



}
.button:hover {
	background-color: #111213;
	color: #C4C4C4;
	cursor: pointer;
	border: none;
}

.button1 {
	width: 230px;
	margin-top: 10px;
	margin-right: auto;
	margin-bottom: 30px;
	margin-left: auto;
	padding-top: 15px;
	padding-right: 10px;
	padding-bottom: 20px;
	padding-left: 10px;
	text-align: center;
	vertical-align: middle;
	border-radius: 0px;
	text-transform: uppercase;
	font-weight: bold;
	letter-spacing: 2px;
	border: 1px solid #FFFFFF;
	color: #FFFFFF;
	transition: all 0.3s linear;
	text-decoration: none;
	display: block;
}
.button1:hover {
	background-color: #111213;
	color: #C4C4C4;
	cursor: pointer;
	border: none;
}

.copyright {
	text-align: center;
	padding-top: 20px;
	padding-bottom: 20px;
	background-color: #111213;
	color: #FFFFFF;
	text-transform: uppercase;
	font-weight: lighter;
	letter-spacing: 2px;
	border-top-width: 2px;
}
.footer_banner {
	padding-bottom: 40PX;
	padding-top: 10px;
	margin-bottom: 0px;
	background-image: url(https://i.imgur.com/BKktXZo.png);nt/uploads/2017/08/Full-HD-s-1080p-4k-HD-New-wallpaper-wpt100556.jpg);
	background-position: center;
	backface-visibility:
	width:100%
	background-repeat: no-repeat;
	background-size: cover;
	
}
footer {
	display: inline-block;
}
.hidden {
	display: none;
}

/* Mobile */
@media (max-width: 320px) {
.logo {
	width: 100%;
	text-align: center;
	margin-top: 13px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
}
	
.container header nav {
	margin-top: 0px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
	width: 100%;
	float: none;
	display: none;
}
header nav ul {
}
nav ul li {
	margin-top: 0px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
	width: 100%;
	text-align: center;
}
.text_column {
	width: 100%;
	text-align: justify;
	padding-top: 0px;
	padding-right: 0px;
	padding-bottom: 0px;
	padding-left: 0px;
	margin-bottom: 20px;
}
.thumbnail {
	width: 100%;
}
.footer_column {
	width: 100%;
	margin-top: 0px;
}
.parallax {
	text-align: center;
	margin-top: 0px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
	padding-top: 40%;
	padding-right: 0px;
	padding-bottom: 0px;
	padding-left: 0px;
	width: 100%;
	font-size: 18px;
}
.parallax_description {
	padding-top: 0px;
	padding-right: 0px;
	padding-bottom: 0px;
	padding-left: 0px;
	width: 90%;
	margin-top: 25px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 12px;
	float: none;
	text-align: center;
}

.tagline {
	margin-top: 20px;
	line-height: 22px;
	font-size: 20px;
	
	
}
.hero_header {
	padding-left: 10px;
	padding-right: 10px;
	line-height: 22px;
	text-align: center;
}
}



/* Small Tablets */
@media (min-width: 321px)and (max-width: 767px) {
.logo {
	width: 100%;
	text-align: center;
	margin-top: 13px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
	color: #FFF;
}
	
.container header nav {

	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
	width: 100%;
	float: none;
	overflow: auto;
	display: inline-block;
	background: #2f6258;
}
header nav ul {
	padding: 0px;
	float: none;
}
nav ul li {
	margin-top: 0px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
	width: 100%;
	text-align: center;
	padding-top: 8px;
	padding-bottom: 8px;
}
.text_column {
	width: 100%;
	text-align: left;
	padding-top: 0px;
	padding-right: 0px;
	padding-bottom: 0px;
	padding-left: 0px;
}
.thumbnail {
	width: 100%;
}
.footer_column {
	width: 100%;
	margin-top: 0px;
}
.parallax {
	text-align: center;
	margin-top: 0px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
	padding-top: 40%;
	padding-right: 0px;
	padding-bottom: 0px;
	padding-left: 0px;
	width: 100%;
	font-size: 18px;
}
.parallax_description {
	padding-top: 0px;
	padding-right: 0px;
	padding-bottom: 0px;
	padding-left: 0px;
	margin-top: 30%;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
	float: none;
	width: 100%;
	text-align: center;
}
.thumbnail {
	width: 50%;
}
.parallax {
	margin-top: 0px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
	padding-right: 0px;
	padding-bottom: 0px;
	padding-left: 0px;
	padding-top: 20%;
}
.parallax_description {
	margin-top: 0px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
	width: 100%;
	padding-top: 30px;
}
.banner {
	padding-left: 20px;
	padding-right: 20px;
}
.footer_column {
	width: 100%;
}
}

/* Small Desktops */
@media (min-width: 768px) and (max-width: 1096px) {
.text_column {
	width: 100%;
}
.thumbnail {
	width: 50%;
}
.text_column {
	width: 100%;
	margin-top: 0px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
	padding-top: 0px;
	padding-right: 0px;
	padding-bottom: 0px;
	padding-left: 0px;
}
.banner {
	margin-top: 0px;
	padding-top: 0px;
}
}
.cc-map-wrapper {
        position: relative;
        padding-bottom: 554px; /* 16:9 */
        padding-top: 25px;
	    height: 0px			
		
}
.cc-map-wrapper iframe {
	
			top: 0;
        left: 0;
        width: 100%;
        height: 113%;
		position: absolute;
} 

.foda{
	position: relative;
	width: 100%;
	float: left;
}

.foda img{
	width 100%;
}
