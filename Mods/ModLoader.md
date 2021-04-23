---
layout: default
title: ModLoader
description: ModLoader description
---

# ModLoader

This is what you need to actually mod the game. That one goes next to the cubeworld.exe and you create a /Mods folder where you put all the other .dll or .cwmod
  
## Side Note

&bull; Legacy Mods compatibility since 26 february 2020

&bull; If you actually want to create a mod, you need to look at this: [CWSDK](https://github.com/ChrisMiuchiz/CWSDK)

## Media

<!--START_SLIDESHOW-->
<body>
<div class="slideshow-container">
 
<div class="mySlides fade">
  <div align="center">
  <img src="https://i.imgur.com/Mxf7nVF.png" style="width:90%">
  </div>
  <div class="text"><u><!--Nothing--></u></div>
</div>

<div class="mySlides fade">
  <div align="center">
  <img src="https://i.imgur.com/Q7fWBku.png" style="width:90%">
  </div>
  <div class="text"><u><!--Nothing--></u></div>
</div>

<div class="mySlides fade">
  <div align="center">
  <img src="https://i.imgur.com/jhRbWXv.png" style="width:90%">
  </div>
  <div class="text"><u><!--Nothing--></u></div>
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

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Original Author Repo:** [ModLoader](https://github.com/ChrisMiuchiz/Cube-World-Mod-Launcher) by [ChrisMiuchiz Cubeworld God](https://github.com/ChrisMiuchiz)

## Comments:
<script src="https://utteranc.es/client.js"
        repo="Paroyer/Comment" 
        issue-term="pathname"
        theme="github-dark"
        label="Comment"
        crossorigin="anonymous"
        async>
</script>  
