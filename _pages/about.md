---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<!-- <head>
<style>
* {box-sizing: border-box}
body {font-family: Verdana, sans-serif; margin:0}
.mySlides {display: none}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 1200px;
  position: relative;
  margin: auto;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

/* Caption text */
.text {
  color: #000000;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/4 etc) */
.numbertext {
  color: #000000;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
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
  .prev, .next,.text {font-size: 11px}
}
</style>
</head>
<body>

<div class="slideshow-container">

<div class="mySlides fade">
  <div class="numbertext">1 / 4</div>
  <img src="images/ucm_ima.png" style="width:100%">
  <div class="text">Universidad Católica del Maule</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 4</div>
  <img src="images/hyp2018.png" style="width:100%">
  <div class="text">Integrantes CI2MA en Hyp2018</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 4</div>
  <img src="images/sn3.png" style="width:100%">
  <div class="text">Santiago Numérico III</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">4 / 4</div>
  <img src="images/svl.png" style="width:100%">
  <div class="text">Mi hijo y yo en Sevilla</div>
</div>

<a class="prev" onclick="plusSlides(-1)">❮</a>
<a class="next" onclick="plusSlides(1)">❯</a>

</div>
<br>

<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span> 
  <span class="dot" onclick="currentSlide(4)"></span> 
</div>

<script>
let slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
}
</script> -->


<link rel="stylesheet" type="text/css" href="https://wowslider.com/sliders/demo-81/engine1/style.css" />
<div id="wowslider-container1">

<div class="ws_images">
<ul>
<li><img src="/images/sn3_960_259.png" alt="Red Kite : bootstrap image slider " title="Santiago Numérico III" id="wows1_0" />Santiago Numérico III</li>
<li><img src="/images/svl_960_259.png" alt="bootstrap slider" title="Yo y mi hijo en Sevilla" id="wows1_1" />Yo y mi hijo en Sevilla</li>
<li><img src="/images/ucm_ima_960_259.png" alt="Hawk : slider bootstrap " title="Universidad Católica del Maule" id="wows1_2" />Universidad Católica del Maule</li>
</ul>
</div>

<div class="ws_bullets">
<div>
<a href="#" title="Santiago Numérico III"><img src="/images/sn3_128.png" alt="/images/sn3.png" />bootstrap range slider </a>
<a href="#" title="Yo y mi hijo en Sevilla"><img src="/images/ucm_ima_128.png" alt="Bald Eagle" />bootstrap 3 slider </a>
<a href="#" title="Hawk"><img src="/images/ucm_ima_128.png" alt="Hawk" />slider for bootstrap </a>
</div>
</div>
<div class="ws_shadow"></div>
</div>

<script type="text/javascript" src="https://wowslider.com/images/demo/wowslider.js"></script>
<script type="text/javascript" src="https://wowslider.com/sliders/demo-81/engine1/script.js"></script>



<div align="justify" class="warning" style='background-color:#E9D8FD; color: #69337A; border-left: solid #805AD5 4px; border-radius: 4px; padding:0.7em;'>
<span>
<p style='margin-top:1em; text-align:center'>
<b>Educación</b></p>
<p style='margin-left:1em;'>
Doctor en Ciencias Aplicadas c/m Ingeniería Matemática
(Ph.D in Applied Mathematics)
Universidad de Concepción, Concepción, Chile, Noviembre 2019.
<br>
Ingeniero Civil Matemático
(Mathematical Engineer)
Universidad de Concepción, Concepción, Chile, Abril 2015.<br>
Licenciado en Ciencias de la Ingeniería Matemática
(Bachelor of Sciences in Mathematical Engineering)
Universidad de Concepción, Concepción, Chile, Julio 2013.
</p>


<p style='margin-top:1em; text-align:center'>
<b>Intereses de investigación (Research Interests)</b></p>
<p style='margin-left:1em;'>
<ul>
<li>Análisis numérico de ecuaciones diferenciales parciales.</li>
<li>Modelamiento matemático de procesos de sedimentación polidispersa.</li>
<li>Sistemas de ecuaciones diferenciales hiperbólicos con productos no conservativos.</li>
<li>Métodos numéricos para sistemas de EDP’s hiperbólicas con productos no conservativos.</li>
<li>Modelos shallow water multicapa para sedimentación polidispersa.</li>
</ul>
</p>

<p style='margin-top:1em; text-align:center'>
<b>Contacto (Contact)</b></p>
<p style='margin-left:1em;'>
Facultad de Ciencias Básicas<br>
Departamento de Matemática, Física y Estadística<br>
Universidad Católica del Maule<br>
Campus San Miguel, Avenida San Miguel 3605<br>
Talca, Chile<br>
email: vosores@ucm.cl
</p>


<p style='margin-bottom:1em; margin-right:1em; text-align:right; font-family:Georgia'> <b>- Víctor Andrés Osores Escalona</b>
</p></span>
</div>
