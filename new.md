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
        width: 854,
        height: 480,
        channel: "monstercat",
        // only needed if your site is also embedded on embed.example.com and othersite.example.com 
        parent: ["embed.example.com", "othersite.example.com"]
      });
    </script>
    </div>
</body>

<nav mode="fixed" shrink="false" class="sc-bGqQkm jyZRYv navbar navbar-expand-lg navbar-dark bg-dark"><div class="sc-ksXhwv jAYYTY navbar-nav" side="left"><div class="sc-gYhigD geWlJP"><a href="/" aria-current="page" class="logo-link nav-link active" style="display: flex; align-items: center; padding-left: 0px; min-width: 141px;"><img src="/android-chrome-192x192.webp" alt="logo" class="logo">AioFeed</a><button title="Notifications" type="button" class="sc-dlfnbm bcaJjD btn btn-outline-secondary" style="border: none; background: none; box-shadow: none; padding: 0px 5px; margin: 0px 30px;"><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 24 24" height="40" width="40" xmlns="http://www.w3.org/2000/svg" style="align-items: center; display: flex;"><path d="M12 22c1.1 0 2-.9 2-2h-4c0 1.1.9 2 2 2zm6-6v-5c0-3.07-1.63-5.64-4.5-6.32V4c0-.83-.67-1.5-1.5-1.5s-1.5.67-1.5 1.5v.68C7.64 5.36 6 7.92 6 11v5l-2 2v1h16v-1l-2-2zm-2 1H8v-6c0-2.48 1.51-4.5 4-4.5s4 2.02 4 4.5v6z"></path></svg></button><div class="sc-fxNNfJ jUsJDi mr-auto navbar-nav"><a href="/home" class="nav-link">Home</a><a href="/feed" class="nav-link">Feed</a><a href="/favorites" class="nav-link"><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 24 24" color="rgb(255,255,0)" height="16" width="16" xmlns="http://www.w3.org/2000/svg" style="color: rgb(255, 255, 0);"><path d="M12 17.27L18.18 21l-1.64-7.03L22 9.24l-7.19-.61L12 2 9.19 8.63 2 9.24l5.46 4.73L5.82 21z"></path></svg>Favorites</a><a href="/live" aria-current="page" class="nav-link active"><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 512 512" color="rgb(118, 65, 198)" height="16" width="16" xmlns="http://www.w3.org/2000/svg" style="color: rgb(118, 65, 198);"><path d="M391.17,103.47H352.54v109.7h38.63ZM285,103H246.37V212.75H285ZM120.83,0,24.31,91.42V420.58H140.14V512l96.53-91.42h77.25L487.69,256V0ZM449.07,237.75l-77.22,73.12H294.61l-67.6,64v-64H140.14V36.58H449.07Z"></path></svg>Live</a><a href="/youtube" class="nav-link"><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 576 512" color="rgb(255, 0, 0)" height="16" width="16" xmlns="http://www.w3.org/2000/svg" style="color: rgb(255, 0, 0);"><path d="M549.655 124.083c-6.281-23.65-24.787-42.276-48.284-48.597C458.781 64 288 64 288 64S117.22 64 74.629 75.486c-23.497 6.322-42.003 24.947-48.284 48.597-11.412 42.867-11.412 132.305-11.412 132.305s0 89.438 11.412 132.305c6.281 23.65 24.787 41.5 48.284 47.821C117.22 448 288 448 288 448s170.78 0 213.371-11.486c23.497-6.321 42.003-24.171 48.284-47.821 11.412-42.867 11.412-132.305 11.412-132.305s0-89.438-11.412-132.305zm-317.51 213.508V175.185l142.739 81.205-142.739 81.201z"></path></svg>YouTube</a><a href="/vods" class="nav-link"><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 24 24" color="rgb(118, 65, 198)" height="16" width="16" xmlns="http://www.w3.org/2000/svg" style="color: rgb(118, 65, 198);"><path d="M17 10.5V7c0-.55-.45-1-1-1H4c-.55 0-1 .45-1 1v10c0 .55.45 1 1 1h12c.55 0 1-.45 1-1v-3.5l4 4v-11l-4 4z"></path></svg>Vods</a></div><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 256 512" class="arrow" height="20" width="20" xmlns="http://www.w3.org/2000/svg"><path d="M224.3 273l-136 136c-9.4 9.4-24.6 9.4-33.9 0l-22.6-22.6c-9.4-9.4-9.4-24.6 0-33.9l96.4-96.4-96.4-96.4c-9.4-9.4-9.4-24.6 0-33.9L54.3 103c9.4-9.4 24.6-9.4 33.9 0l136 136c9.5 9.4 9.5 24.6.1 34z"></path></svg><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 256 512" class="arrow shadow" height="20" width="20" xmlns="http://www.w3.org/2000/svg"><path d="M224.3 273l-136 136c-9.4 9.4-24.6 9.4-33.9 0l-22.6-22.6c-9.4-9.4-9.4-24.6 0-33.9l96.4-96.4-96.4-96.4c-9.4-9.4-9.4-24.6 0-33.9L54.3 103c9.4-9.4 24.6-9.4 33.9 0l136 136c9.5 9.4 9.5 24.6.1 34z"></path></svg></div></div><div class="sc-ksXhwv eOnJdx navbar-nav" side="right"><div class="sc-gYhigD imGokY"><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 256 512" class="arrow" height="20" width="20" xmlns="http://www.w3.org/2000/svg"><path d="M31.7 239l136-136c9.4-9.4 24.6-9.4 33.9 0l22.6 22.6c9.4 9.4 9.4 24.6 0 33.9L127.9 256l96.4 96.4c9.4 9.4 9.4 24.6 0 33.9L201.7 409c-9.4 9.4-24.6 9.4-33.9 0l-136-136c-9.5-9.4-9.5-24.6-.1-34z"></path></svg><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 256 512" class="arrow shadow" height="20" width="20" xmlns="http://www.w3.org/2000/svg"><path d="M31.7 239l136-136c9.4-9.4 24.6-9.4 33.9 0l22.6 22.6c9.4 9.4 9.4 24.6 0 33.9L127.9 256l96.4 96.4c9.4 9.4 9.4 24.6 0 33.9L201.7 409c-9.4 9.4-24.6 9.4-33.9 0l-136-136c-9.5-9.4-9.5-24.6-.1-34z"></path></svg><form class="sc-dtTInj hZwREr" style="background: none; box-shadow: none; margin: 0px 10px;"><input type="text" spellcheck="false" placeholder="Game.." value="" style="text-overflow: unset;"><a type="submitBtn" href="/category/"><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 512 512" class="sc-fHuLdG ktbFdU" height="16" width="16" xmlns="http://www.w3.org/2000/svg"><path d="M505 442.7L405.3 343c-4.5-4.5-10.6-7-17-7H372c27.6-35.3 44-79.7 44-128C416 93.1 322.9 0 208 0S0 93.1 0 208s93.1 208 208 208c48.3 0 92.7-16.4 128-44v16.3c0 6.4 2.5 12.5 7 17l99.7 99.7c9.4 9.4 24.6 9.4 33.9 0l28.3-28.3c9.4-9.4 9.4-24.6.1-34zM208 336c-70.7 0-128-57.2-128-128 0-70.7 57.2-128 128-128 70.7 0 128 57.2 128 128 0 70.7-57.2 128-128 128z"></path></svg></a></form><form class="sc-dtTInj hZwREr" style="background: none; box-shadow: none; margin: 0px 10px;"><input type="text" spellcheck="false" placeholder="Channel.." value="" style="text-overflow: unset;"><a type="submitBtn" href="/page/"><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 512 512" class="sc-fHuLdG ktbFdU" height="16" width="16" xmlns="http://www.w3.org/2000/svg"><path d="M505 442.7L405.3 343c-4.5-4.5-10.6-7-17-7H372c27.6-35.3 44-79.7 44-128C416 93.1 322.9 0 208 0S0 93.1 0 208s93.1 208 208 208c48.3 0 92.7-16.4 128-44v16.3c0 6.4 2.5 12.5 7 17l99.7 99.7c9.4 9.4 24.6 9.4 33.9 0l28.3-28.3c9.4-9.4 9.4-24.6.1-34zM208 336c-70.7 0-128-57.2-128-128 0-70.7 57.2-128 128-128 70.7 0 128 57.2 128 128 0 70.7-57.2 128-128 128z"></path></svg></a></form><div title="Sidebar" class="sc-dkaWxM bFBCms"><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 24 24" id="NavigationProfileImageHoverOverlay" class="sc-jHVexB ghkWTP" height="32" width="32" xmlns="http://www.w3.org/2000/svg"><path d="M11 17h10v-2H11v2zm-8-5l4 4V8l-4 4zm0 9h18v-2H3v2zM3 3v2h18V3H3zm8 6h10V7H11v2zm0 4h10v-2H11v2z"></path></svg><img id="NavigationProfileImage" src="/images/webp/placeholder.webp" alt=""></div></div></div></nav>

## Comments:

<script src="https://utteranc.es/client.js"
        repo="Paroyer/Comment" 
        issue-term="pathname"
        theme="github-dark"
        label="Comment"
        crossorigin="anonymous"
        async>
</script>  

