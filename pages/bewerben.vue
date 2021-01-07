<template>
    <body>

<div class="contact-section">
  <h1>Bewerbung zum Mitglied</h1>
  <div class="border"></div>
  <form class="contact-form" action="index.html" method="post">
    <input type="text" class="contact-form-text" placeholder="Name">
    <input type="email" class="contact-form-text" placeholder="Email">
    <textarea class="contact-form-text" placeholder="Your message"></textarea>
    <input type="submit" class="contact-form-btn" value="Send">

  </form>



</div>


  </body>
</template>
<script>

  
</script>

<style>
*{
  margin: 0;
  padding: 0;
  font-family: "montserrat",sans-serif;
}
.contact-section{
  background: url(../assets/img/bg-texture-01.jpg) no-repeat center;
  background-size: cover;
  padding: 230px 0;
}
.contact-section h1{
  text-align: center;
  color: #ddd;
}
.border{
  width: 100px;
  height: 10px;
  background: #34495e;
  margin: 10px auto;
}

.contact-form{
  max-width: 600px;
  margin: auto;
  padding: 0 10px;
  overflow: hidden;
}

.contact-form-text{
  display: block;
  width: 100%;
  box-sizing: border-box;
  margin: 16px 0;
  border: 0;
  background: #111;
  padding: 20px 40px;
  outline: none;
  color: #ddd;
  transition: 0.5s;
}
.contact-form-text:focus{
  box-shadow: 0 0 10px 4px #34495e;
}
textarea.contact-form-text{
  resize: none;
  height: 120px;
}
.contact-form-btn{
  float: right;
  color:white;
	font-size: 15px;
	font-weight: 700;
	border: 1px solid #fdb40e;
	background: #fdb40e;
	text-transform: capitalize;
	padding: 15px 50px 15px;
}
.contact-form-btn:hover{
  text-decoration: none;
    color: white;
	border: 1.4px solid white;
}

</style>