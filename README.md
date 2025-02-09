
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>K Tech Solutions</title>
<link rel="icon" type="image/png" href="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQppIjRgvVCErBvMUnUAvDeW5PcuxgirxNh7g&s">
</head>
<style>
  * {box-sizing: border-box;}
body {font-family: Verdana, sans-serif;}
.mySlides {display: none;}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  width: 100%;
  height: 200px;
  position: relative;
  margin: auto;
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  height: 15px;
  width: 100%;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active {
  background-color: #717171;
}

/* Fading animation */
.fade {
  animation-name: fade;
  animation-duration: 1.5s;
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .text {font-size: 11px}
}

   
    /* Reset some default styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: whitesmoke;
    line-height: 1.6;
    background-color: black;
}

header {
    background:black;
    color: #20ebd1;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style-type: none;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: #20ebd1;
    text-decoration: none;
    padding: 5px 10px;
    border-radius: 200px;
    transition: background-color 0.8s;
   
}

nav ul li a:hover {
    background-color: rgba(255, 255, 255, 0.2);
}
 .slider {
  position: relative;
  width: 600px; /* adjust the width */
  height: 400px; /* adjust the height */
}

.slides {
  display: flex;
  transition: transform 0.5s ease;
}

.slides img {
  width: 100%;
  height: 100%;
}

.prev, .next {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  background-color: #fff;
  border: none;
  padding: 10px;
  cursor: pointer;
}

.prev {
  left: 0;
}

.next {
  right: 0;
}

.social-links {
  position: absolute;
  bottom: 0;
  left: 50%;
  transform: translateX(-50%);
  display: flex;
  justify-content: space-between;
  width: 200px; /* adjust the width */
}

.social-links img {
  width: 30px; /* adjust the width */
  height: 30px; /* adjust the height */
  margin: 10px;
}
.hello{
    height: 240px;
    width: 100%;
    background-color: #20ebd1;
    padding: 20px;
    font-family: cursive;
    text flex-wrap: revert;

}
.h1{
    text-align: center;
}
.services {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    margin-top:10px;
}

.service {
    background-color:green;
    padding: 40px;
    margin: 2px;
    margin-top: 1px;
    margin-right: 70%;
    scale: 100%;

    width: calc(80%-30%);
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    border-radius:90px;
}

.service h2 {
    color: #20ebd1;
    font-size: 2em;
    margin-bottom: 10px;
}

.service p {
    color:#20ebd1;
    font-size: 1.1em;
    line-height: 1.6;
}
div.hey{
    background-color:#f00f0f ;
    text-align: center;
    font-family: serif;

}
  .navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #333;
  color: #fff;
  padding: 1rem;
}

.logo {
  font-size: 1.5rem;
  font-weight: bold;
}

.nav-links {
  list-style: none;
  display: flex;
}

.nav-links li {
  margin-right: 20px;
}

.nav-links a {
  color: #fff;
  text-decoration: none;
  transition: color 0.3s ease;
}

.nav-links a:hover {
  color: #007bff;
}

.burger {
  display: none;
  cursor: pointer;
}

.burger div {
  width: 25px;
  height: 3px;
  background-color: #fff;
  margin-bottom: 5px;
}

@media (max-width: 768px) {
  .nav-links {
    display: none;
  }
  .burger {
    display: block;
  }
}

.container {
  max-width: 1200px;
  margin: 40px auto;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.box {
  width: calc(33.33% - 20px);
  margin: 10px;
  padding: 20px;
  background-color: #f7f7f7;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  opacity: 0;
  transform: scale(0.5);
  animation: animate-box 1s forwards infinite alternate;
}

.box h2 {
  font-size: 18px;
  margin-bottom: 20px;
  color: #333;
}

.box ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

.box li {
  margin-bottom: 10px;
  color: #666;
}

.box button {
  background-color: #007bff;
  color: #fff;
  border: none;
  padding: 10px 20px;
  font-size: 18px;
  cursor: pointer;
  border-radius: 10px;
}

.box button:hover {
  background-color: #0056b3;
}

@keyframes animate-box {
  0% {
    opacity: 0;
    transform: scale(0.5);
  }
  100% {
    opacity: 1;
    transform: scale(1);
  }
}
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active {
  background-color: #717171;
}

/* Fading animation */
.fade {
  animation-name: fade;
  animation-duration: 1.5s;
}

@keyframes fade {
  from {opacity: .4}
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .text {font-size: 11px}
}

div.kath{
  width: 100%;
  height: 260px;
  background-color: #31d9cf;
  justify-content: center;
  align-content: center;
}
.fade {
  position: relative;
  width: 300px;
  height: 200px;
  border: 1px solid #ddd;
}

.product-info, .product-action {
  position: absolute;
  width: 100%;
  height: 100%;
  transition: opacity 0.5s;
}

.product-info {
  background-color: #fff;
  z-index: 2;
}

.product-action {
  background-color: #4CAF50;
  color: #fff;
  opacity: 0;
}

.fade:hover .product-info {
  opacity: 0;
}

.fade:hover .product-action {
  opacity: 1;
}  




</style>
<script> function loadHomeContent() { const contentDiv = document.getElementById('content'); contentDiv.innerHTML = ` <h2>Welcome to K Tech Solutions</h2> <p>This is the home content. Here you can add all the information you want your visitors to read.</p> <p>Feel free to customize this content as per your needs.</p> `; } </script> </head>
<body>

  <div class="abcd">
   
  </div>
    <header>
        <nav class="navbar">
  <div class="logo">K Tech Solutions</div>
  <ul class="nav-links">
   
  <div class="navbar">
    <li><a href="home.html">Home</a></li>
    <li><a href="services.html">Services</a></li>
    <li><a  href="about.html">Join Affiliate Program</a></li>
     <li><a href="contactus.html">Contact Us</a></li>
     </div> <div id="content" class="content">  </div>
</ul>
  <div class="burger">
    <div class="line1"></div>
    <div class="line2"></div>
    <div class="line3"></div>
  </div>
</nav>

    </header>
   
   <div class="hello">
   <h1 class="h1">Welcome to K Tech Solutions</h1>
<div class="container">
  <div class="box animated-box">
    <h2>Your One-Stop Shop for Freelance Services</h2>
  </div>
  <div class="box animated-box">
    <h2>Founded by Huzaifa Kath, K Tech Solutions is a global freelance services platform that connects clients with top talent from around the world.</h2>
  </div>
  <div class="box animated-box">
    <h2>Fast, Reliable, and Global</h2>
  </div>
  <div class="box animated-box">
    <h2>At K Tech Solutions, we understand the importance of timely project delivery. That's why we guarantee completion of projects within just 3 hours.</h2>
  </div>
  <div class="box animated-box">
    <h2>Your Partner for Success</h2>
  </div>
  <div class="box animated-box">
    <h2>Our platform offers a wide range of freelance services, including:</h2>
    <ul>
      <li>Content creation</li>
      <li>Graphic design</li>
      <li>Web development</li>
      <li>Digital marketing</li>
      <li>And many more!</li>
    </ul>
  </div>
  <div class="box animated-box">
    <h2>Why Choose K Tech Solutions?</h2>
    <ul>
      <li>Fast project delivery (within 3 hours)</li>
      <li>Global talent pool</li>
      <li>High-quality services</li>
      <li>Competitive pricing</li>
      <li>24/7 customer support</li>
    </ul>
  </div>
  <div class="box animated-box">
    <button>Get Started Today!</button>
  </div>
</div>

 




 
 
 
<script>
let slideIndex = 0;
showSlides();
<script>
 const express = require('express');
const app = express();

app.get('/home', (req, res) => {
  res.send('<h1>Welcome to K Tech Solutions</h1>');
});

app.get('/services', (req, res) => {
  res.send('<h1>Our Services</h1><ul><li>Content creation</li><li>Graphic design</li><li>Web development</li></ul>');
});

app.get('/portfolio', (req, res) => {
  res.send('<h1>Our Portfolio</h1><p>Coming soon...</p>');
});

app.get('/about', (req, res) => {
  res.send('<h1>About Us</h1><p>We are a global freelance services platform...</p>');
});

app.get('/contact', (req, res) => {
  res.send('<h1>Get in Touch</h1><p>contact@ktechsolutions.com</p>');
});

app.listen(3000, () => {
  console.log('Server started on port 3000');
});
app.use(express.static('public'));
let slideIndex = 0;
showSlides();

function showSlides() {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}    
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
  setTimeout(showSlides, 2000); // Change image every 2 seconds
}
</script>


<script>
let slideIndex = 0;
showSlides();

function showSlides() {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}    
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
  setTimeout(showSlides, 2000); // Change image every 2 seconds
}
</script>


</body>
</html>
