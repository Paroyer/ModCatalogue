---
layout: default
title: CommandsMod
description: CommandsMod description
---

# CommandsMod 

This mod implements additional commands into Cube World. It also adds the ability to use the arrow keys to get messages you have previously sent, like how most command lines work.

## Known Bugs and/or Conflict


## Compatibility Table
  
<div align="center" markdown="1">

| Version :               | CWSDK-7.1     | CWSDK-6.1  | CWSDK-5.1   |
| :-----------:           |:-------------:| :---------:| :----------:|
| CommandMod.dll          |    &#10003;   | &#10003;   | &#10003;    |


</div>
  
## Side Note

## Media
<!--START_SLIDESHOW-->
<body>
<div class="slideshow-container">
 
<div class="mySlides fade">
  <div align="center">
  <img src="https://raw.githubusercontent.com/Paroyer/ModCatalogue/gh-pages/assets/images/Mods/help1.png?token=ANK6PU2YCM4PGZVCB3GKV4TAQIU2I" style="width:90%">
  </div>
  <div class="text"></div>
</div>

<div class="mySlides fade">
  <div align="center">
  <img src="https://raw.githubusercontent.com/Paroyer/ModCatalogue/gh-pages/assets/images/Mods/help2.png?token=ANK6PU7LH634XVEBR6JQCDDAQIU2O" style="width:90%">
  </div>
  <div class="text"></div>
</div>

<div class="mySlides fade">
  <div align="center">
  <img src="https://raw.githubusercontent.com/Paroyer/ModCatalogue/gh-pages/assets/images/Mods/help3.png?token=ANK6PU3XFZNMQ2GFYV2ZCVTAQIU2W" style="width:90%">
  </div>
  <div class="text"></div>
</div>

<div class="mySlides fade">
  <div align="center">
  <img src="https://raw.githubusercontent.com/Paroyer/ModCatalogue/gh-pages/assets/images/Mods/help4.png?token=ANK6PUZ2VGXZ2WIORXI2JL3AQIU3A" style="width:90%">
  </div>
  <div class="text"></div>
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

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Original Author Repo:** [CommandMod](https://github.com/ChrisMiuchiz/Cube-World-Commands-Mod) by [ChrisMiuchiz Cubeworld God](https://github.com/ChrisMiuchiz)

## Comments:
<script src="https://utteranc.es/client.js"
        repo="Paroyer/Comment" 
        issue-term="pathname"
        theme="github-dark"
        label="Comment"
        crossorigin="anonymous"
        async>
</script>  
