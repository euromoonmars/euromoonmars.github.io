---
layout: page
title: CHILL-ICE Analogue Astronaut Mission
---

<h1>Overview</h1>
<h2>Iceland Analogue Astronaut campaign 2020-2021</h2>

Have you ever wondered how we will establish a Moon or even a Mars base in the near future? Or what is needed to actually start living on another celestial body? EuroMoonMars is a non-profit analogue astronaut organization, which is focussed on getting answers to these questions and establishing a clear image of the future. 

The main focus on conventional analog missions is to investigate how a crew of up to 6 astronauts fares on a mission of 1 week to 6 months. This includes scientific research in various disciplines but also aspects of mental health and crew sociology.

CHILL-ICE (Construction of a Habitat Inside a Lunar-Analogue Lava-tube) is a new kind of analogue astronaut mission. It focuses on the important first hours after landing where potential emergencies and risks will be the highest for the astronauts.  Our mission next year is to build and deploy a safe and working habitat inside a lava tube in just over 8 hours! 

However, of course, these research missions don't come without a cost. Developing a habitat, power & communication systems and space suits that meet the needed requirements will constitute 75% of the costs. Additional costs will be composed of food, the housing of the support crews and travel expenses to and within Iceland. 

<h1>Contact</h1>

If you would like to know more about this mission please follow EuroMoonMars on LinkedIn, Instagram and Facebook or send us an email at <a href="mailto: charlotte.pouwels@euromoonmars.space">charlotte.pouwels(at)euromoonmars.space</a>

If you would like to support this initiative, please donate at <a href="https://www.gofundme.com/f/chillice-analogue-astronaut-mission?utm_medium=copy_link&utm_source=customer&utm_campaign=p_lico+share-sheet">GoFundMe</a>.


<h1>Image Gallery</h1>

<div class="slideshow-container">

<div class="mySlides fade">
  <div class="numbertext">1 / 4</div>
  <img src="/Chillice/photo1.jpeg" style="width:100%">
  <!--div class="text">Lavaman</div-->
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 4</div>
  <img src="/Chillice/photo2.jpeg" style="width:100%">
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 4</div>
  <img src="/Chillice/photo3.jpeg" style="width:100%">
</div>

<div class="mySlides fade">
  <div class="numbertext">4 / 4</div>
  <img src="/Chillice/photo4.jpeg" style="width:100%">
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
