body {
background-image: url("wp7733426.png");
"
)
)
");
	background-size: 2.5%;
}

h1 {
	color: orange;
}

table {
	border: 3px solid black;
	margin:auto;
	text-align: center;
}

th {
	background-color: orange;
	font-size: 36px;
}

/*	
p {
	color:red;
	font-weight: 1000;
	}
*/
a {
	color: blue;
	transition: color 2s;
}

a:hover {
	color: crimson;
}

a:active {
	color: black;
}

a:visited {
	text-decoration-color: green;
}

a:focus {
	color: orange;
}
	
.play_btn {
	color: green;
	transition: color 5s;
	font-size: 40px;
}

.play_btn:hover {
	color: black;
	font-size: 40px;
}

.pause_btn {
	color: gray;
	font-size: 50px;
}

.pause_btn:hover {
	color: black;
	font-size: 50px;
}

.h_img {
	width: 200px;
	transition: width 5s ease-in-out;
}

.h_img:hover {
	width: 180px;
}

.player {
	margin-left: auto;
	margin-right: auto;
	min-height: 300px;
	width: 200px;
	background-color: #DDDDDDDD;
	text-align: center;
}

.player_btns {
	background-color: #DFDFDFDD;
	border: 1px solid black;
	border-radius: 0px 0px 15px 15px;
}

.player_window {
	border: 1px solid black;
	border-radius: 15px 15px 0px 0px;
	min-height: 300px;
}

.vert_slider {
	transform: rotate(270deg);
}

.form_bg {
	background-color: #FFFFFFCC;
	background-color: rgba(255, 255, 255, 80%);
	width: 100%;
}




iframe {
	width: 100%;
	aspect-ratio: 16 / 9;
}

.para_1_style {
	color: red;
	font-size: 16px;
	padding-left: 50px;
	padding-right: 50px;
	padding-top: 50px;
	padding-bottom: 50px;
/*	border: dashed 10px purple;*/
}
.para_2_style {	color: orange;	font-size: 16px; /*	padding: 50px;*/ /*	border: dashed 10px purple;*/ 	margin: 20px;	border: 50px; }


.red {
	color: red;
}
.orange {
	color: orange;
}
.yellow {
	color: yellow;
}

.header {
	border: 1px solid black;
	border-radius: 0px;
	background-color: rgba(255, 255, 255, 50%);
}

.nav {
	border: 1px solid black;
	background-color: cyan;
	background-image: url("images/tilec.png");
	background-size: 2%;
	background-repeat: repeat-x;
	background-position: center bottom;
}

.red_circle {
	width: 100px;
	height: 100px;
	background: radial-gradient(circle, green, crimson, orange, blue);
	border-radius: 0px 25px 0px 25px;
	color: white;
	border: 10px dashed black;
	margin-left: 30%;
}

.article {
	float: left;
	min-width: 59%;
	min-height: 300px;
	border: 1px solid black;
}

.section {
	border: 1px solid black;
}

.aside {
	min-width: 39%;
	min-height: 300px;
	float: right;
	border: 1px solid black;
	background-color: #FFFFFFCC;
}


.footer {
	border: 1px solid black;
	background-color: #FFFFFFCC;
}

.circle_b {
	width: 100px;
	height: 100px;
	border: 5px solid black;
	border-radius: 50%;
	background-color: red;
	transition: background-color 5s, width 5s, height 5s;
}

.circle_b:hover {
	width: 90px;
	height: 90px;
	border: 5px solid black;
	border-radius: 50%;
/*  background-color: purple; */
	animation: five_color 5s linear infinite;
}

@keyframes five_color {
	0% {
		background-color: red;
	}
	20% {
		background-color: orange;
	}
	40% {
		background-color: green;
	}
	60% {
		background-color: yellow;
	}
	80% {
		background-color: purple;
