--
layout: post
title:  Penkesu Computer Fork - Part 1: Soldering
catagories: [blog, Projects]
tags: [July, 2022, July 2022, Computer Projects, Raspberry Pi, Obsidian]
date: 7th July, 2022
---
The first part of the guide deals with soldering, which has taken up a substantial part of the early build time. Because of the nature of the mechanical keyboard substituted and also for the keyboard chosen in the original build, soldering is an essential skill for the project. After ordering parts for the project (which due to supply change issues took some work), I quickly realized that soldering a few things together would be the beginning not the end of the project.

# Practice makes perfect
Mechanical keyboards and the various parts associated with building them have a deserved reputation as expensive. Because mistakes in the assembly process can cause the parts to become unusable, it is a good idea to become proficient with soldering before taking a soldering iron to your keyboard.

## light up badges
The first project I undertook was a simple (and hopefully cheap) [[https://www.makershed.com/products/learn-to-solder-skill-badge-kit|badge]] soldering project. I fried the first board and so had to do a second run. This was a pretty essential experience as it taught me to respect the boards I was working on. The second pass resulted in a successful badge.
[[Picture]]
Alternative kits are available from [[https://www.adafruit.com/product/5495|ada fruit]] and [[https://www.sparkfun.com/products/14637|Sparkfun]]/

## Adding complexity
I still was really uncomfortable so the director of our maker space gave me another kit to do before I started on the keyboard. This was another badge kit, but one that lit up my name, and required a lot more soldering. Soldering the parts together was a good experience because I got way better at soldering as the project went along.
[[picture]]
Unfortunately the kit is discontinued. These hour glass kits [[https://www.amazon.com/Gikfun-Electronic-Hourglass-Welding-Practice/dp/B078BP1S4D|1]] [[https://www.robotshop.com/en/osepp-hourglass-diy-solder-kit.html|2]] [[https://www.etsy.com/listing/1148801393/electronic-hourglass-kit-soldering-kit|3]], and learn to solder kits [[https://www.amazon.com/Elenco-AmeriKit-Learn-Solder-Kit/dp/B0009Z3JJA|1]] are a good place to start.

# Tackling the board.
After about 3 hours practicing soldering, I felt comfortable enough to give soldering the border a go. The night before I found a build guide for the pancake on [[https://www.reddit.com/r/MechanicalKeyboards/comments/dyh7fc/pancake_build_log_including_some_measurements/|reddit]], or rather I found the [[https://imgur.com/a/titpc1n#TYYEaDg|imagur guide embedded in a reddit post. That guide had a lot of good practical advice for building the keyboard. Including that the black line on the diode goes towards the square hole. I think if you get this wrong it won't work. Soldering the 48 diodes took abut an 2 hours, which is a similar time length to this build video I found on youtube.

## Control

Once the diodes were soldered, I moved on to partially assembling the control chip a adrino micro pro. One that was done, I flashed the firm ware -> more on that in the second guide and tested sockets. There should be a way to do this prior to assembling your board, but I wasn't able to find a guide on it.

## Switches
The board tested I next went on to solder in the switches at which point
