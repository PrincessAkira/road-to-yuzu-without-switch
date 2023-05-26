# road-to-yuzu-without-switch

This Repo explains how to install the yuzu Ninendo Switch Emulator without a Switch on a Windows PC, while I distance myself from piracy and that I own any of these Games shown in the original screenshots and Gifs!  
If you use anything out of this please credit me appropriately!

[![Twitter URL](https://img.shields.io/twitter/url?label=Follow%20me&style=social&url=https%3A%2F%2Ftwitter.com%2Fpoolpartyakali)](https://twitter.com/PoolPartyAkali)

[Ryujinx Version](https://github.com/PrincessAkira/road-to-ryujinx-without-switch)

-  [Introduction](#introduction)
-  [Guide](#guide)
-  [yuzu&nbsp;Setup](#setup)
-  [files](#files)
-  [Settings](#settings)
-  [Games](#games)
-  [dump-games](#dump-games)
-  [Additional](#additional)
-  [Compatability](#compatibility)
-  [Game&nbsp;Updates](#game-updates)
-  [Uninstalling&nbsp;Game&nbsp;Updates](#Uninstalling-Game-Updates)
-  [Log&nbsp;Files](#log-files)
-  [BCAT](#bcats)
-  [Shaders](#shaders)
-  [Mods/Patches](#mods)
-  [Goodbye](#goodbye)

# Introduction

Hey, im Sarah and I'm writing you a guide on how to install yuzu without having a Switch, since I discovered this is literally a pain in the ass.  
 I try to make it as easy as possible, but be sure to check this out if you need new keys, since I try to keep this always up-to-date! <3

# Guide

# Manual Setup

## Setup

First you will need [yuzu](https://pineappleea.github.io/).
Download it.
Open it in WinRar, 7ZIP idk and then move the contents in a folder and open the yuzu.exe.

yuzu will open and show this screen.
![DuBistDoof](https://lh3.googleusercontent.com/yvQRYqP0L1iKsmBQpbCPXZjcfRkQAMzZczD0_Wfp3sGWIp0XFs1izPUoeoVfX86Etg9-0qxVaI7jed5pm3beCySCyu_0Rf1KC7OPs-URJ4-ujjwxIbnV8Ncd2tDaBaBcxuvP87_Z0Q=w2400)  
 On there click `Emulation -> Configure -> System -> Profile`
Then press on Add and make a new profile, then close yuzu

## Files

Inside of yuzu click `File -> Open yuzu folder`.
This will open the yuzu configuration folder inside of explorer.

Create a folder called "keys" and copy the keyfile you got from [Reddit](https://www.reddit.com/r/NewYuzuPiracy/) or anywhere else in there.
`Note: The File name should be prod.keys, not prod.keys.txt`

## Settings

For settings open yuzu up `Emulation -> Configure -> Graphics, Select OpenGL and set it to Vulkan or OpenGL`. With the new improvements since this guide came out, Vulkan is now a viable option!  
 Then go to Controls and press Single Player yadiyadiyada and set it to something like this
![Reeeeeeee](https://lh3.googleusercontent.com/E-G_UZ68lgO48D2WsKYkfLXkMtdaIz425k_pk3m0oHNjLWJZLghl9s5JNvJdXFFr54FRoeJNBd3uF2bfbxnZyd1Fc8NiHhI804sERIjQO0Uz0JmnKy0hONVLDqxDk06zKG6OHtprBg=w2400)

Then Press Configure and set Player 1 to Pro Controller if you have a controller/keyboard and to Joycons if Joycons.
Press Configure and press the excat buttons on your controller (it's easier for Xbox but for you PS4 and keyboard users I have a graphic for yo found [here](https://compass-ssl.xboxlive.com/assets/c7/a1/c7a12fbe-af04-4a90-92f2-18338219c2aa.png?n=one-controller-front-l.png))
After you're done press Okay and continue to the next step.

## Games

Download any ROM you want from any ROM Website you like, or if your arent a pirate, dump it from your Switch.  
 After you got your File (can be .xci or .nsp) create a folder somewhere on your PC and in that folder create another folder for your game.  
 After that double-click into yuzu and select the folder you put your game folder in.  
 ![UwU](https://lh3.googleusercontent.com/f2SYBEgKuTBUgBwjJLeOhq8lq3uxcWVZChzW9L6JTaazTajurg8HdzoZbnPkkTmPxiOrqCZd5gM8EJb8eWEMxw16BThmQWTdCMKmqd-q0-YJwEohfGx14q4VBcj3vQEoyfS-F0ER0Q=w2400)

## Dump-Games

I found a very good guide that can be found [here](https://wiki.no-intro.org/index.php?title=Nintendo_Switch_Dumping_Guide)
Sorry, I just don't have a Homebrewed Switch to try it atm.
When you have the XCI, just do the same as in the Gif Above

# Additional

## Compatibility

For a Compatibility List of Games working look [here](https://yuzu-emu.org/game/)

## Game-Updates

Download the update of your game or DLCs, usually as a .nsp.
Put it in your folder of the game, then open yuzu. To install it, follow the steps in this GIF.  
 ![rererere](https://lh3.googleusercontent.com/I9RStHr7wBFJKr_sXMwEC5D6YI4bBocfcSeDOlmrdzQhsLCCDR7OG0SKuUaFxu7NEh5vTHIACHa34Jdots8TPJX7N2oLgMrOHwPFsXVF1VbBu8GkZ7782QpC6Itte5eTwlBdYUs0Rg=w2400)  
 If it says that it is already installed, your ROM likely already has that DLC/Update preinstalled, don't worry, if it breaks the game, just follow the steps in the next section.

## Uninstalling-Game-Updates

Open yuzu, and find the game that has an update that you want to uninstall.  
 Then follow the steps of the GIF below.  
 ![uninstall](https://lh3.googleusercontent.com/1v74IY9WRJZ6Xly8hShVk0g_aUHce8TE1EWin3nvx2IF57rvFp4gOQIzk9jL1ZtIWeO_eYOOamwWVhs3az5kUCXzlCw4bM0oVUr6PY-av1UPxKm1JF_EryilSrUqQDd7RX9oWTHYWA=w2400)  
 If it says that there are no updates to uninstall, that means exactly what it says, there are no preinstalled updates, and no manually user-installed updates either.

## Log-files

-  Windows: Open the Run prompt (Windows Key + R) and type this in, "%appdata%\yuzu" then head to the logs directory
-  MacOS: How about waiting until yuzu comes out on MacOS.......
-  Linux: Open your file manager of choice, make sure that Show Hidden Files is ENABLED, and head to the following directory, "/home/YourUsername/.local/share/yuzu" and open the logs directory.

# BCATS

Whats a BCAT?
It stands for BoxCat and it's Nintendo's sending you Ingame Gifts.  
 On an Emulator this, obv, doesn't work like it would on a Switch, due to the emulator not connecting to Nintendo's servers.  
 To work around this, Yuzu has its own way of giving you these.  
 To easiernable this go in the menu and choose Boxcat. ![here](https://lh3.googleusercontent.com/2Q8pASe7g3DstMOK91lZxXZv-2k5ixef_SfQeMXn7Sg0hvG1i265u45qro8LU_4KiYHTU9m7u4gProHXoG4et-TU3Q_mozX84Z3NJxX9uym547lT-reeKCIRalDudtNlm5p22oha0Q=w2400)  
 A list of all the stuff you can get can be found [here](https://yuzu-emu.org/help/feature/boxcat/)

# Shaders

So to get Shaders go [here](https://github.com/JENOVAAbsolute/128BB-Shaders).
Download the one you need and then Right Click on the Game -> Open Transferable Pipeline Cache -> Paste Contents in

# Mods

Here ima show how to install mods.
It's pretty simple, as an example, we're gonna take the mod from [here](https://gbatemp.net/threads/pokemon-mystery-dungeon-dx-60-fps-mod.559469/).  
 When you download the zip file you will have a folder called "exefs_patches".  
 Go inside that folder and in the other folder in there until you are at this file with an .IPS
![memememem](https://nuke.bayern/QTwbBtLy.png?key=GP1JZ3BylhCn9q)  
 Then move that IPS file into exefs_patches and delete the now empty folder, then rename exefs_patches into exefs.  
 Now open yuzu and `Right click your game -> Open Mod Directory`.  
 Create a new folder with the name that you want for the patch (you can name it anything you want).  
 Then move the exefs folder into the folder that you just made, then restart yuzu and you're done.  
 You now see your mod at compatibility.

There are multiple sites to get Mods altogether.

-  https://drive.google.com/drive/folders/1dY20qH3phqoUfmAEdngTzrtMIvPFwSG4?usp=sharing

-  https://github.com/theboy181/switch-ptchtxt-mods

-  https://github.com/yuzu-emu/yuzu/wiki/Switch-Mods

-  Additional Note here:
   If you got any other names for the folder don't rename it to exefs.
   Instead rename them to romfs or romfs_ext.

# Goodbye

Thank you for reading this, I hope it helped you with your start into Switch emulation.
If I forgot something just create a Pull Request with the stuff added and I will review it ASAP.

# List of contributers to the document :D

PrincessAkira Owner, created this page  
 MGThePro Cleaned up some stuff, fixed typos and links
Mou-Ikkai Fixed a gif
Descent098 Helped clarify the settings to use for the key
sanikdah Cleaned up some images, typos, and wrote this section and the uninstall updates section
