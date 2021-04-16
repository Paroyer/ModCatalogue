---
layout: default
title: ChangeSpecializationMod
description: ChangeSpecializationMod description
---

# ChangeSpecializationMod 

Let you change specialization via a chat command,

/trans class <class_type>

/trans spec <0\|1>

## Known Bugs and/or Conflict


## Compatibility Table
  
<div align="center" markdown="1">

| Version :                  | CWSDK-7.1     | CWSDK-6.1  | CWSDK-5.1   |
| :-----------:              |:-------------:| :---------:| :----------:|
| ChangeSpecializationMod.dll|    &#10003;   |            |             |


</div>
  
## Side Note

&bull; Still have to test if that work with custom classes like the monk and such

## Media Placeholder
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

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Original Author Repo:** [CubeWorldMods](https://github.com/ZaneYork/CubeWorldMods) by [ZaneYork](https://github.com/ZaneYork)

\*One repo for all his mods, just drag and drop the .dll you actually want\*

## Comments:
<script src="https://utteranc.es/client.js"
        repo="Paroyer/Comment" 
        issue-term="pathname"
        theme="github-dark"
        label="Comment"
        crossorigin="anonymous"
        async>
</script>  

