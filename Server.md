---
layout: default
title: Server
description: Server description
---
# Server

## How to Create a Server with the CommandsMod

The CommandsMod allow you to open a server using your SteamID that anyone can join. To do a proper server running 24/7 you will need a dedicated computer and steam account with another purchased copy of CubeWorld, but you can still just turn it on/off when you need to and use your own account. If you have a dedicated computer for this you can always create a new scheduled task to reboot the computer every X hours/days, and if you use the auto login on the steam app just drop a cubeworld shortcut inside your Windows StartUp folder and the game will open itself. Please Note that you will still have to click continue and then type /server open, if ever people start hosting server for the Release version it could be achievable to create a mod that makes it automatic.

### Server specific Commands:

> /join \[SteamID/Alias\] -- Let you join someone server via their SteamID or an alias specified in Mods\CommandsMod\join.txt
> 
> /server open -- Allow anyone to join you with your steam ID or a set alias
> 
> /server close -- Stop allowing anyone to join your session
> 
> /server block -- Refuse all new sessions
> 
> /server blacklist -- Enable blacklisting Steam IDs specified in Mods\CommandsMod\blacklist.txt
> 
> /server log -- Log new session requests

### Find your SteamID:

Multiple way to do it, directly from you [steam account detail page](https://store.steampowered.com/account/) just check under your account name you should see SteamID: 12345678901234567.

You could also look someone else SteamID from the [SteamCalculator](https://steamdb.info/calculator/) if you know their account name.

Once you have a Server ID you can set an alias in Mods\CommandsMod\join.txt with this format:

>\[SteamID\] DesiredAlias
>
>
>For exemple:
>
>76561199012927661 philrd_server

### Side Note

You could create a custom server spawn or what not using the BuildingMod and sharing the .cwb save file with your friends, it's located inside Mods\BuildingMod\Saves\

## Comments:

<script src="https://utteranc.es/client.js"
        repo="Paroyer/Comment" 
        issue-term="pathname"
        theme="github-dark"
        label="Comment"
        crossorigin="anonymous"
        async>
</script>  

