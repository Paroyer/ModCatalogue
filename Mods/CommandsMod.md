---
layout: default
title: CommandsMod
description: CommandsMod description
---

# CommandsMod 

>This mod implements additional commands into Cube World. It also adds the ability to use the arrow keys to get messages you have previously sent, like how most command lines work.

## Known Bugs and/or Conflict


## Compatibility Table
  
<div align="center" markdown="1">

| Version :               | CWSDK-7.1     | CWSDK-6.1  | CWSDK-5.1   |
| :-----------:           |:-------------:| :---------:| :----------:|
| CommandMod.dll          |    &#10003;   | &#10003;   | &#10003;    |


</div>
  
## Side Note

>## Commands:
> #### Get help
>  
>    /help [page number]
>
> ---
> 
> #### Display world coordinates
>  
>    /coords
>    
> ---
> 
> #### Teleport in terms of map coordinates
>
>    /tp <x> <y>
> 
> ---
> 
> #### Teleport to another player
>
>    /tp <name>
> 
> ---
> 
> #### Set time
> 
>    /settime <hour>:<minute>
>    
> ---
> 
> #### Set name
> 
>    /name <name>
>    
> ---
> 
> #### Connect to a server via steam ID
> 
>    /join <Steam ID>
>    
> ---
> 
> #### Connect to a server using an alias, specified in Mods\CommandsMod\join.txt
> 
>    /join <alias>
>    
> ---
> 
> #### Allow anyone to connect to your server
> 
>    /server open
>    
> ---
> 
> #### Stop allowing anyone to connect to your server
> 
>    /server close
>    
> ---
> 
> #### Refuse all new sessions
> 
>    /server block
>    
> ---
> 
> #### Enable blacklisting Steam IDs specified in Mods\CommandsMod\blacklist.txt
> 
>    /server blacklist
>    
> ---
> 
> #### Log new session requests
> 
>    /server log
>    
> ---
> 
> #### Teleport to your cursor position on the map
> 
>    /tpmap
>	
> ---
> 
> #### Create a waypoint/home you can teleport to 
> 
>    /sethome <alias>
>	
> ---
> 
> #### Teleport to a waypoint/home
> 
>    /home <alias>
>	
> ---
>
> #### Change chat size
> 
>    /gui chat <x size> <y size>
>	
> ---
> 
> #### Use a skill - This will also tell you the identifier of the skill, if available.
> 
>    /skill <id>
>    
> ---
> 
> #### Play a sound
> 
>    /sound <id> <volume> <speed>
>    

## Media
<!--START_SLIDESHOW-->
<body>
<div class="slideshow-container">
 
<div class="mySlides fade">
  <div align="center">
  <img src="https://i.imgur.com/rCt9sNe.png" style="width:90%">
  </div>
  <div class="text"></div>
</div>

<div class="mySlides fade">
  <div align="center">
  <img src="https://i.imgur.com/WXk4t25.png" style="width:90%">
  </div>
  <div class="text"></div>
</div>

<div class="mySlides fade">
  <div align="center">
  <img src="https://i.imgur.com/WpHmNoS.png" style="width:90%">
  </div>
  <div class="text"></div>
</div>

<div class="mySlides fade">
  <div align="center">
  <img src="https://i.imgur.com/ixWi98q.png" style="width:90%">
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
