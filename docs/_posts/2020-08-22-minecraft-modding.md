---
layout:    post
title:     "Minecraft Modding"
date:      2020-08-22 20:49:59 +0100
published: true
category:  parenting
tags:      coding programming minecraft frustration gaming parenting family
---
Finally one of the kids (J) wanted to learn some coding with me! He's been watching a ton of YouTube videos and decided he would like to be able to make Minecraft mods.

<!--more-->

We got cracking with what looked like an up-to-date tutorial. First we tried the latest version of the Minecraft Forge MDK (Mod Development Kit). The tutorial code didn't work. Okay no problem.. we got hold of the older version, that works with Minecraft 1.12.2. Followed the tutorial through and ran the game, our custom item showed up! J found this pretty exciting, even though our item was displayed as a pink and black chequerboard to show that the game didn't know how to draw it.

Next we tried to add a texture file for the item, to make it look like the fancy pickaxe it was supposed to be. J spent a bunch of time creating a very vividly coloured pickaxe image. However, try as we may we could not get it to show up. J was surprisingly patient but I was starting to worry I was going to put him off!

I then spent a few hours retyping the whole thing carefully from the tutorial, thinking I must've made an error. Same result unfortunately. Next up I tried following a different tutorial which looked a little bit more comprehensive. And... I got exactly the same problem at the end of it.

Fast forward another few hours and I finally worked out that something had broken in the MDK version we had, which had been released since both tutorials had been written. I tried one from last year and it worked. Phew! Still time to rescue J's interest. So then we switched to applying the fix to his project on his computer. And we hit another problem, this time we could not get Eclipse to recognise the updated Gradle build file.

I'm hoping to actually get J's custom rainbow pickaxe up and running for him tomorrow.

On the bright side it has been lovely to spend time with him on something creative and to be teaching him. I really noticed how quickly he picked things up. I've also been very impressed with his patience, which he definitely needed! I hope this experience has not put him off too badly.

  - [First tutorial we tried](https://codakid.com/guide-to-minecraft-modding-with-java/)
  - [Second tutorial we tried, more comprehensive](https://cubicoder.github.io/tutorials/1-12-2/tutorials/)
    - I did leave [a comment](http://disq.us/p/2bd622d) in case anyone else could benefit from our suffering!
  - [MDK version that actually worked - 14.23.5.2847](https://files.minecraftforge.net/maven/net/minecraftforge/forge/1.12.2-14.23.5.2847/forge-1.12.2-14.23.5.2847-mdk.zip)
  - [It's not just us - SO discussion of the Eclipse problem](https://stackoverflow.com/questions/60512749/eclipse-gradle-project-shows-dependency-errors-the-container-project-and-exte)