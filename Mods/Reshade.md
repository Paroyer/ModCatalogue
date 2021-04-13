---
layout: default
title: Reshade
description: Reshade description
---

# Reshade Pack

Reshade pack for cubeworld release that look more like alpha

## Known Bugs and/or Conflict

## Side Note

## Media
<!--START_SLIDESHOW-->
<body>
<div class="slideshow-container">
 
<div class="mySlides fade">
<p align="center"><iframe style="width:90%" width="560" height="315" src="https://www.youtube.com/embed/ltSMXiBFMDw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></p>
  <div class="text"><!--Nothing--></div>
</div>

<div class="mySlides fade">
  <div align="center">
  <img src="https://preview.redd.it/70cre8lr3gr61.png?width=1920&format=png&auto=webp&s=694df0f8e1967412abc14347920c49d4936311c1" style="width:90%">
  </div>
  <div class="text"><u>A view of the dusk sky under a castle</u></div>
</div>

<div class="mySlides fade">
  <div align="center">
  <img src="https://preview.redd.it/ix0h6g806gr61.png?width=1920&format=png&auto=webp&s=82940214807e2a8c6bbb04e3f8546770ff32a7ca" style="width:90%">
  </div>
  <div class="text"><u>Cozy village next to the snowlands</u></div>
</div>

<a class="prev" onclick="plusSlides(-1)">&#10094;</a>
<a class="next" onclick="plusSlides(1)">&#10095;</a>
</div>
<br>
<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span> 
</div>
<!--START_SCrIPT-->
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
  </body>
<!--END_SLIDESHOW_&_SCRIPT-->

## Links

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Original Author Repo:** [Cubeworld Enhanced_Atmosphere](https://drive.google.com/file/d/1j0E0t8KR29ywYzL49iB6_4_h1t2qrXwP/view?usp=sharing) by [Pikyso](https://www.reddit.com/r/CubeWorld/comments/mkzp5k/cube_world_enhanced_atmosphere_official_launch/)

## Comments:
<script src="https://utteranc.es/client.js"
        repo="Paroyer/Comment" 
        issue-term="pathname"
        theme="github-dark"
        label="Comment"
        crossorigin="anonymous"
        async>
</script>  
