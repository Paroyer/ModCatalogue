---
layout: default
title: BetterMap
description: BetterMap description
---

# BetterMap

Concept Mod based on Geo CT, using the CWSDK, turbo simple just writeByte at the address needed. Just to show that even a monkey with a computer can do a simple mod using the last version of the CWSDK.

## Known Bugs and/or Conflict

&bull; Setting arent saved between session, you have to reactivate the map modification you want each relaunch, but kinda minor Imma fix this some day.
 
## Compatibility Table
  
<div align="center" markdown="1">

| Version :               | CWSDK-7.1     | CWSDK-6.1  | CWSDK-5.1   |
| :-----------:           |:-------------:| :---------:| :----------:|
| BetterMap.dll           | 	&#10003;     |            |             |

</div>
  
## Side Note

## Media
<!--START_SLIDESHOW-->
<body>
<div class="slideshow-container">
 
<div class="mySlides fade">
  <div align="center">
  <img src="https://media.discordapp.net/attachments/641283888798367754/826462677484175441/MaxZoomRot.png" style="width:90%">
  </div>
  <div class="text"><u>Max Zoom and Rotation</u></div>
</div>

<div class="mySlides fade">
  <div align="center">
  <img src="https://raw.githubusercontent.com/Paroyer/BetterMap/master/README/ShowQuestIcons.png" style="width:90%">
  </div>
  <div class="text"><u>QuestIcons</u></div>
</div>

<div class="mySlides fade">
  <div align="center">
  <img src="https://raw.githubusercontent.com/Paroyer/BetterMap/master/README/ShowQuestNames.png" style="width:90%">
  </div>
  <div class="text"><u>QuestNames</u></div>
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

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Original Author Repo:** [BetterMap](https://github.com/Paroyer/BetterMap) by [Paroyer](https://github.com/Paroyer)


## Comments:
<script src="https://utteranc.es/client.js"
        repo="Paroyer/Comment" 
        issue-term="pathname"
        theme="github-dark"
        label="Comment"
        crossorigin="anonymous"
        async>
</script>  
