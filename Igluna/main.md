---
layout: page
title: IgLuna 2019 Campaign
---

<p style="font-size:25px">
	IgLuna is the first ESA Lab inter-University demonstrator project, and is hosted by the Swiss Space Centre (SSC) with the vision to create an analogue habitat inside lunar ice caps.
</p>

The campaigns were held from 17–30 June 2019, and involved 18 student teams from 9 countries across Europe. The students developed modular demonstrators and tested them during a field test conducted inside the moon-like extreme environment of the Glacier Palace inside the Matterhorn glacier.

<h1>The Mission</h1>

Two teams of Euromoonmars members took part in Igluna 2019: a science team (VUSE) from VU Amsterdam and the <a href="/Artmoonmars/main">Moon Gallery</a>.

VUSE performed multiple science experiments, including successful studies of the deformation of ice crystals, bacterial inside the ice, and plant growth with moon soil in cold conditions. VUSE team published multiple abstracts on international conferences (e.g. LPSC, EPSC, IAC) and provided BSc and MSc research projects for students at VU Amsterdam. A total of 6 students of VUSE performed the project at the Igluna Campaign. During this campaign the team gathered results and presented the project for audience, ESA general director Jan Woerner, and VIP guests (including Apollo 17 astronaut Harrison Schmitt).

Thanks to VUSE team members: Marc Heemskerk (coordinator), Bram de Winter (coordinator), Stijn van Bloois, Robin Bas Korthouwer, Maarten Berg, Marjolein Daeter, Dieke Beentjes, Amanda Kruijver, Arlene Dingemans, Tinka Clement, and Bram Albers

Thanks to: Swiss Space Center (Tatiana Benevides), ILEWG/ESA (prof. Bernard Foing) and our sponsors (ILEWG, Cosine, Euromex, HE Space)

<h1>Contact</h1>

vuigluna@gmail.com

<h1>Image Gallery</h1>

<i>Source: <a href="https://www.spacecenter.ch/igluna/previouseditions/">Swiss Space Centre</a></i>
<br>

<div class="slideshow-container" align="center">

<div class="mySlides fade">
  <div class="numbertext">1 / 7</div>
  <img src="/Igluna/logo.jpg" style="width:75%">
  <!--div class="text">Lavaman</div-->
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 7</div>
  <img src="/Igluna/mainpic.jpg" style="width:75%">
  <!--div class="text">Lavaman</div-->
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 7</div>
  <img src="/Igluna/photo1.jpg" style="width:75%">
  <!--div class="text">Lavaman</div-->
</div>

<div class="mySlides fade">
  <div class="numbertext">4 / 7</div>
  <img src="/Igluna/photo2.jpg" style="width:75%">
</div>

<div class="mySlides fade">
  <div class="numbertext">5 / 7</div>
  <img src="/Igluna/photo3.jpg" style="width:75%">
</div>

<div class="mySlides fade">
  <div class="numbertext">6 / 7</div>
  <img src="/Igluna/photo4.jpg" style="width:75%">
</div>

<div class="mySlides fade">
  <div class="numbertext">7 / 7</div>
  <img src="/Igluna/photo5.jpg" style="width:75%">
  <!--div class="text">Lavaman</div-->
</div>

<a class="prev" onclick="plusSlides(-1)">&#10094;</a>
<a class="next" onclick="plusSlides(1)">&#10095;</a>

</div>
<br>

<script>
var slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
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
</script>
