---
layout: default
title: swag
description: swag description
---
# swag

## VideoPlaylistTest

<p align="center"><iframe style="width:90%" width="560" height="315" src="https://www.youtube.com/embed/videoseries?list=PLWy0Jf96bIqw9sCG-mPfAsVko9J9CCXsn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></p>
<body>
    <div style="position:relative; margin-left:-20%;">
    <!-- Add a placeholder for the Twitch embed -->
    <div id="twitch-embed"></div>
    <!-- Load the Twitch embed script -->
    <script src="https://embed.twitch.tv/embed/v1.js"></script>
    <!-- Create a Twitch.Embed object that will render within the "twitch-embed" root element. -->
    <script type="text/javascript">
      new Twitch.Embed("twitch-embed", {
        width: 90%,
        height: 90%,
        channel: "monstercat",
        // only needed if your site is also embedded on embed.example.com and othersite.example.com 
        parent: ["embed.example.com", "othersite.example.com"]
      });
    </script>
    </div>
</body>

<div class="twitch">
  <div class="twitch-video">
    <iframe
      src="https://player.twitch.tv/?channel=phil_nash&parent=philna.sh&autoplay=false"
      frameborder="0"
      scrolling="no"
      allowfullscreen="true"
      height="100%"
      width="100%">
    </iframe>
  </div>
  <div class="twitch-chat">
    <iframe
      frameborder="0"
      scrolling="no"
      src="https://www.twitch.tv/embed/phil_nash/chat?parent=philna.sh"
      height="100%"
      width="100%">
    </iframe>
  </div>
</div>

## Comments:

<script src="https://utteranc.es/client.js"
        repo="Paroyer/Comment" 
        issue-term="pathname"
        theme="github-dark"
        label="Comment"
        crossorigin="anonymous"
        async>
</script>  

