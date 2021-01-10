<template>
    <body>
	<div class="container">
		<div class="contact-box">
			<div class="left">
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2572.6642840453014!2d8.351064715879849!3d49.8487652384157!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47bd85d36dd2da53%3A0x56f987f2d52e9f0f!2sGermany-playsgroup%20e.V.!5e0!3m2!1sde!2sde!4v1610207066108!5m2!1sde!2sde" width="100%" height="auto" frameborder="0" style="border:;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>
            </div>
			<div class="right">
				<h2>Kontakt</h2>
				<input type="text" class="field" placeholder="Vorname*">
                <input type="text" class="field" placeholder="Nachname*">
				<input type="text" class="field" placeholder="Email*">
				<input type="text" class="field" placeholder="Telefonnummer*">
				<textarea placeholder="Nachricht*" class="field"></textarea>
				<button class="btn">Abschicken</button>
			</div>
		</div>
	</div>
    
</body>

</template>

<style>

*{
	padding: 0;
	margin: 0;
	box-sizing: border-box;
	font-family: 'Quicksand', sans-serif;
}

body{
	height: 100vh;
	width: 100%;
    background-image: url(../assets/img/bg-texture-01.jpg);
}

.container{
	position: relative;
	width: 100%;
	height: 100%;
	display: flex;
	justify-content: center;
	align-items: center;
	padding: 20px 100px;
}

.container:after{
	content: '';
	position: absolute;
	width: 100%;
	height: 100%;
	left: 0;
	top: 0;
	background: url("") no-repeat center;
	background-size: cover;
	filter: blur(50px);
	z-index: -1;
}
.contact-box{
	max-width: 850px;
	display: grid;
	grid-template-columns: repeat(2, 1fr);
	justify-content: center;
	align-items: center;
	text-align: center;
	background-color: #fff;
	box-shadow: 0px 0px 19px 5px rgba(0,0,0,0.19);
}

.left{
	background: url("") no-repeat center;
	background-size: cover;
	height: 100%;
}
.left iframe{
    height: 100%;
    width: 100%;
}


.right{
	padding: 25px 40px;
}

h2{
	position: relative;
	padding: 0 0 10px;
	margin-bottom: 10px;
}

h2:after{
	content: '';
    position: absolute;
    left: 50%;
    bottom: 0;
    transform: translateX(-50%);
    height: 4px;
    width: 50px;
    border-radius: 2px;
    background-color: #2ecc71;
}

.field{
	width: 100%;
	border: 2px solid rgba(0, 0, 0, 0);
	outline: none;
	background-color: rgba(230, 230, 230, 0.6);
	padding: 0.5rem 1rem;
	font-size: 1.1rem;
	margin-bottom: 22px;
	transition: .3s;
}

.field:hover{
	background-color: rgba(0, 0, 0, 0.1);
}

textarea{
	min-height: 150px;
}

.btn{
	width: 100%;
	padding: 0.5rem 1rem;
	background-color: #2ecc71;
	color: #fff;
	font-size: 1.1rem;
	border: none;
	outline: none;
	cursor: pointer;
	transition: .3s;
}

.btn:hover{
    background-color: #27ae60;
}

.field:focus{
    border: 2px solid rgba(30,85,250,0.47);
    background-color: #fff;
}

@media screen and (max-width: 880px){
	.contact-box{
		grid-template-columns: 1fr;
	}
	.left{
		height: 200px;
	}
}
</style>