---
layout: default
title: CubeGression
description: CubeGression description
---

# CubeGression 

Artifacts give combat boosts

## Known Bugs and/or Conflict


## Compatibility Table
  
<div align="center" markdown="1">

| Version :               | CWSDK-7.1     | CWSDK-6.1  | CWSDK-5.1   |
| :-----------:           |:-------------:| :---------:| :----------:|
| CubeGression.dll        |    &#10003;   |            |             |


</div>
  
## Side Note

## Media Placeholder
<!--START_SLIDESHOW-->
<body>
<div class="slideshow-container">

<div class="mySlides fade">
  <div align="center">
  <img src="https://raw.githubusercontent.com/Paroyer/ModCatalogue/gh-pages/assets/images/Mods/Cubegression.png?token=ANK6PU7QDFAMG5Q3B7Y42B3AQIVL4" style="width:90%">
  </div>
  <div class="text"><u>New Stats</u></div>
</div>

<a class="prev" onclick="plusSlides(-1)">&#10094;</a>
<a class="next" onclick="plusSlides(1)">&#10095;</a>
</div>
<br>
<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
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

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Original Author Repo:** [Cubegression-Light](https://github.com/thetrueoneshots/Cubegression-Light) by [Nichiren](https://github.com/thetrueoneshots)

## Comments:
<script src="https://utteranc.es/client.js"
        repo="Paroyer/Comment" 
        issue-term="pathname"
        theme="github-dark"
        label="Comment"
        crossorigin="anonymous"
        async>
</script>  
