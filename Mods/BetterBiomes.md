---
layout: default
title: BetterBiomes
description: BetterBiomes description
---

# BetterBiomes

A terrain generation mod for CubeWorld.

## Known Bugs and/or Conflict

- Known to remove 1 kind of biome from the game
- 
- In MP if the other player dont have the mod one of you will probably see the other one way up in the sky

## Compatibility Table
  
<div align="center" markdown="1">

| Version :               | CWSDK-7.1     | CWSDK-6.1  | CWSDK-5.1   |
| :-----------:           |:-------------:| :---------:| :----------:|
| BetterBiomes-1.0        |               |            |             |
| BetterBiomes-1.1        |               |            |  &#10003;   |
| BetterBiomes-FanUpdate  | 	&#10003;    |            |             |

</div>
  
## Side Note

## Media
<!--START_SLIDESHOW-->
<body>
<div class="slideshow-container">
 
<div class="mySlides fade">
<p align="center"><iframe style="width:90%" width="560" height="315" src="https://www.youtube.com/embed/KYpNPXEdgfI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></p>
  <div class="text"><!--Nothing--></div>
</div>

<div class="mySlides fade">
  <div align="center">
  <img src="https://raw.githubusercontent.com/ParanormalVibe/BetterBiomes/master/Before.PNG" style="width:90%">
  </div>
  <div class="text"><u>Before</u></div>
</div>

<div class="mySlides fade">
  <div align="center">
  <img src="https://raw.githubusercontent.com/ParanormalVibe/BetterBiomes/master/After.PNG" style="width:90%">
  </div>
  <div class="text"><u>After</u></div>
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

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Original Author Repo:** [BetterBiomes](https://github.com/ParanormalVibe/BetterBiomes) by [Julyuary](https://github.com/ParanormalVibe)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**FanUpdate:** [BetterBiomes-FanUpdate](https://github.com/Paroyer/BetterBiomes-FanUpdate) 

## Comments:
<script src="https://utteranc.es/client.js"
        repo="Paroyer/Comment" 
        issue-term="pathname"
        theme="github-dark"
        label="Comment"
        crossorigin="anonymous"
        async>
</script>  
