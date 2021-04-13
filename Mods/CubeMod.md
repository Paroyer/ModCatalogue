---
layout: default
title: CubeMod
description: CubeMod description
---

# CubeMod 

A Cube World mod adding item/enemy scaling, useful artifact stats, modified item spawn rates, and pvp. Let you /setcenter and scale mob/item with distance.

## Known Bugs and/or Conflict

&bull; Artifacts are shown multiple time in the top left bar

## Compatibility Table
  
<div align="center" markdown="1">

| Version :               | CWSDK-7.1     | CWSDK-6.1  | CWSDK-5.1   |
| :-----------:           |:-------------:| :---------:| :----------:|
| cubemod.cwmod           |    &#10003;   |            |             |

\*As a legacy mod it's directly compatible with the last version of the modloader, dont use the .dll wrapper \*

</div>
  
## Side Note

&bull; Be carefull on the Repo link, the latest version shown on the right side is 1.0. Actually it's 1.02, check all Release to be sure.

## Media Placeholder
<!--START_SLIDESHOW-->
<body>
<div class="slideshow-container">
  
<div class="mySlides fade">
<p align="center"><iframe style="width:90%" width="560" height="315" src="https://www.youtube.com/embed/5-30AJhvIrc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></p>
  <div class="text"><!--Nothing--></div>
</div>

<div class="mySlides fade">
<p align="center"><iframe style="width:90%" src='https://thumbs.gfycat.com/HonoredSereneEwe-mobile.mp4' frameborder='0' scrolling='no' allowfullscreen width='640' height='404'></iframe></p>
  <div class="text"><!--Nothing--></div>
</div>

<div class="mySlides fade">
  <div align="center">
  <img src="https://i.imgur.com/H7WvwiN.png" style="width:90%">
  </div>
  <div class="text"><u>EnemyScaling</u></div>
</div>

<div class="mySlides fade">
  <div align="center">
  <img src="https://i.imgur.com/G1Z7k8i.png" style="width:90%">
  </div>
  <div class="text"><u>Stats</u></div>
</div>

<div class="mySlides fade">
  <div align="center">
  <img src="https://i.imgur.com/LsQf9fq.png" style="width:90%">
  </div>
  <div class="text"><u>ItemScaling</u></div>
</div>

<a class="prev" onclick="plusSlides(-1)">&#10094;</a>
<a class="next" onclick="plusSlides(1)">&#10095;</a>
</div>
<br>
<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span>
  <span class="dot" onclick="currentSlide(4)"></span>
  <span class="dot" onclick="currentSlide(5)"></span> 
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

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Original Author Repo:** [cubemod](https://github.com/arishackstv/cubemod) by [ArishHack](https://github.com/arishackstv)

## Comments:
<script src="https://utteranc.es/client.js"
        repo="Paroyer/Comment" 
        issue-term="pathname"
        theme="github-dark"
        label="Comment"
        crossorigin="anonymous"
        async>
</script>  
