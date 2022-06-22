<template>
<div>
	<nav class="flex bg-blue-700 h-14 w-100 justify-between">
      <div class="flex justify-start font-bold text-white p-4 h-14">
        <img src="../assets/images/logo1.png" alt="" />
        ChelseaNG Fan Page
      </div>
      <!-- <h2 class="text-2xl font-semibold m-10"> Welcome to Zinny's coffee shop </h2> -->
      <ul class="flex justify-center items-center text-l text-white font-bold">
        <a class="mx-2" href="/">HOME</a>
        <!-- <a class="mx-2" href="#banana">banana</a> -->
      </ul>
    </nav>
<div class="main"> 
	
    <title>Slide Navbar</title>
	<!-- <link rel="stylesheet" type="text/css" href="slide navbar style.css"> -->
<link href="https://fonts.googleapis.com/css2?family=Jost:wght@500&display=swap" rel="stylesheet">

	 	
		<input type="checkbox" id="chk" aria-hidden="true">

			<div class="signup">
				<form>
					<label for="chk" aria-hidden="true">Sign up</label>
					<input type="text" name="txt" placeholder="User name" required="">
					<input type="email" name="email" placeholder="Email" required="">
					<input type="password" name="pswd" placeholder="Password" required="">
					<button>Sign up</button>
				</form>
			</div>

			<div class="login">
				<form>
					<label for="chk" aria-hidden="true" >Login</label>
					<input type="email" name="email" placeholder="Email" required="">
					<input type="password" name="pswd" placeholder="Password" required="">
					<button>Login</button>
				</form>
			</div>
	</div>

	 <div
        class="div1 flex m-8 items-center justify-center space-x-8 text-blue-700 bg-white"
      >
        <span class="iconify" data-icon="dashicons:facebook-alt"></span>
        <span class="iconify" data-icon="dashicons:instagram"></span>
        <span class="iconify" data-icon="arcticons:twitter"></span>
        <span class="iconify" data-icon="iconoir:youtube"></span>
      </div>
      <div class="flex space-x-8 justify-center items-center text-blue-700">
        <div><a href="#" target="_blank">Contact Us</a></div>
        <div><a href="#" target="_blank">Modern Slavery Act</a></div>
        <div><a href="#" target="_blank">FAQs</a></div>
        <div><a href="#" target="_blank">Careers</a></div>
        <div><a href="#" target="_blank">Privacy Policy</a></div>
        <div><a href="#" target="_blank">Cookie Policy</a></div>
        <div><a href="#" target="_blank">Terms and Conditions</a></div>
      </div>
      <div class="flex space-x-8 justify-center items-center text-blue-700 p-8">
        <span class="iconify" data-icon="ic:outline-copyright"></span>2022
        Chelsea FC. All rights reserved. No part of this site may be reproduced
        without our written permission.
      </div>
	
</div>
</template>

<script>
export default {
    name: "LogIn"
    
}
</script>

<style scoped>
body{
	margin: 0;
	padding: 0;
	display: flex;
	justify-content: center;
	align-items: center;
	min-height: 100vh;
	font-family: 'Jost', sans-serif;
	background: linear-gradient(to bottom, #0f0c29, #302b63, #24243e);
}
.main{
	width: 350px;
	height: 500px;
	background: red;
	overflow: hidden;
	background: url("https://doc-08-2c-docs.googleusercontent.com/docs/securesc/68c90smiglihng9534mvqmq1946dmis5/fo0picsp1nhiucmc0l25s29respgpr4j/1631524275000/03522360960922298374/03522360960922298374/1Sx0jhdpEpnNIydS4rnN4kHSJtU1EyWka?e=view&authuser=0&nonce=gcrocepgbb17m&user=03522360960922298374&hash=tfhgbs86ka6divo3llbvp93mg4csvb38") no-repeat center/ cover;
	border-radius: 10px;
	box-shadow: 5px 20px 50px #000;
	margin: 0 auto;
	position: relative;
	top:50px;
}
#chk{
	display: none;
}
.signup{
	position: relative;
	width:100%;
	height: 100%;
}
label{
	color: #fff;
	font-size: 2.3em;
	justify-content: center;
	display: flex;
	margin: 60px;
	font-weight: bold;
	cursor: pointer;
	transition: .5s ease-in-out;
}
input{
	width: 60%;
	height: 20px;
	background: #e0dede;
	justify-content: center;
	display: flex;
	margin: 20px auto;
	padding: 10px;
	border: none;
	outline: none;
	border-radius: 5px;
}
button{
	width: 60%;
	height: 40px;
	margin: 10px auto;
	justify-content: center;
	display: block;
	color: white;
	background: blue;
	font-size: 1em;
	font-weight: bold;
	margin-top: 20px;
	outline: none;
	border: none;
	border-radius: 5px;
	transition: .2s ease-in;
	cursor: pointer;
}
button:hover{
	background: blue;
}
.login{
	height: 460px;
	background: #eee;
	border-radius: 60% / 10%;
	transform: translateY(-180px);
	transition: .8s ease-in-out;
}
.login label{
	color: blue;
	transform: scale(.6);
}

#chk:checked ~ .login{
	transform: translateY(-500px);
}
#chk:checked ~ .login label{
	transform: scale(1);	
}
#chk:checked ~ .signup label{
	transform: scale(.6);
}


</style>