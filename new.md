---
layout: default
title: swag
description: swag description
---
# swag

## VideoPlaylistTest

<p align="center"><iframe style="width:90%" width="560" height="315" src="https://www.youtube.com/embed/videoseries?list=PLWy0Jf96bIqw9sCG-mPfAsVko9J9CCXsn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></p>
<body>
    <div style="width:800px; margin:0 auto;">
    <!-- Add a placeholder for the Twitch embed -->
    <div id="twitch-embed"></div>
    <!-- Load the Twitch embed script -->
    <script src="https://embed.twitch.tv/embed/v1.js"></script>
    <!-- Create a Twitch.Embed object that will render within the "twitch-embed" root element. -->
    <script type="text/javascript">
      new Twitch.Embed("twitch-embed", {
        width: 854,
        height: 480,
        channel: "monstercat",
        // only needed if your site is also embedded on embed.example.com and othersite.example.com 
        parent: ["embed.example.com", "othersite.example.com"]
      });
    </script>
    </div>
</body>

## Comments:

<script src="https://utteranc.es/client.js"
        repo="Paroyer/Comment" 
        issue-term="pathname"
        theme="github-dark"
        label="Comment"
        crossorigin="anonymous"
        async>
</script>  

