---
layout: default
title: BrightNight
description: BrightNight description
---

# BrightNight

>Stops nights from becoming pitch black, time 20:40 is the darkest it'll ever get

## Known Bugs and/or Conflict


## Compatibility Table
  
<div align="center" markdown="1">

| Version :               | CWSDK-7.1     | CWSDK-6.1  | CWSDK-5.1   |
| :-----------:           |:-------------:| :---------:| :----------:|
| BrightNight.cwmod       |    &#10003;   |            |             |

\*As a legacy mod it's directly compatible with the last version of the modloader, dont use the .dll wrapper \*

</div>
  
## Side Note

Just put the .cwmod inside the /Mods folder and it automaticaly apply, there's no command/config.

## Media
<!--START_SLIDESHOW-->
<body>
<div class="slideshow-container">
 
<div class="mySlides fade">
  <div align="center">
  <img src="https://i.imgur.com/TKknDq4.png" style="width:90%">
  </div>
  <div class="text"><u>Before</u></div>
</div>

<div class="mySlides fade">
  <div align="center">
  <img src="https://i.imgur.com/VAawbhm.png" style="width:90%">
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

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Original Author Link:** [BrightNight](https://www.dropbox.com/s/t97k1jyihe6iihw/BrightNight.cwmod) by [Frognik](https://www.reddit.com/r/CubeWorld/comments/dhokj2/frogniks_cube_world_mods/)

## Comments:
<script src="https://utteranc.es/client.js"
        repo="Paroyer/Comment" 
        issue-term="pathname"
        theme="github-dark"
        label="Comment"
        crossorigin="anonymous"
        async>
</script>  
