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
The first project I undertook was a simple (and hopefully cheap) [badge soldering project](https://www.makershed.com/products/learn-to-solder-skill-badge-kit|badge) . I fried the first board and so had to do a second run. This was a pretty essential experience as it taught me to respect the boards I was working on. The second pass resulted in a successful badge.
[[Picture]]
Alternative kits are available from [ada fruit](https://www.adafruit.com/product/5495) and [Sparkfun](https://www.sparkfun.com/products/14637).

## Adding complexity
I still was really uncomfortable so the director of our maker space gave me another kit to do before I started on the keyboard. This was another badge kit, but one that lit up my name, and required a lot more soldering. Soldering the parts together was a good experience because I got way better at soldering as the project went along.
[[picture]]
Unfortunately the kit is discontinued. These hour glass kits [[https://www.amazon.com/Gikfun-Electronic-Hourglass-Welding-Practice/dp/B078BP1S4D|1]] [[https://www.robotshop.com/en/osepp-hourglass-diy-solder-kit.html|2]] [[https://www.etsy.com/listing/1148801393/electronic-hourglass-kit-soldering-kit|3]], and learn to solder kits [[https://www.amazon.com/Elenco-AmeriKit-Learn-Solder-Kit/dp/B0009Z3JJA|1]] are a good place to start.

# Tackling the board... first try.
After about 3 hours practicing soldering, I felt comfortable enough to give soldering the border a go. The night before I found a build guide for the pancake on [[https://www.reddit.com/r/MechanicalKeyboards/comments/dyh7fc/pancake_build_log_including_some_measurements/|reddit]], or rather I found the [[https://imgur.com/a/titpc1n#TYYEaDg|imagur guide embedded in a reddit post. That guide had a lot of good practical advice for building the keyboard. Including that the black line on the diode goes towards the square hole. I think if you get this wrong it won't work. Soldering the 48 diodes took abut an 2 hours, which is a similar time length to this build video I found on youtube.

## Control

Once the diodes were soldered, I moved on to partially assembling the control chip a adrino micro pro. One that was done, I flashed the firmware -> more on that in the second guide and tested sockets.

## Switches
The board tested I next went on to solder in the switches at which point I realized that I had assembled I realized that I needed to unsolder the microcontroller from the PCB to install all the switches. At this point I realized that the project is really only feasible with testing, if sockets rather than the included headers. I was able to sell the unusable (for me) board to a keyboard enthusiast for a small ammount, and I reordered a microcontroller and kit.

### I should mention...
That [MKUltra](mkultra.click) provided exemplary customer services, catching a comment in their discord and providing proactive customer service. It was really amazing. They also give you cool stickers. In purchasing components [little keyboards](url) also stood out and caught errors in my order providing proactive customer service.

# Tacking The Board Second Try
I approached the second run through with a lot more confidence, which was a mistake. I wound up frying another microcontroller right off the bat, but because of the sockets I was able to go and replace the microcontroller without tossing another PCB.

## Socketing
[[image of sockets]]
The sockets were amazing but still had a bit of a learning curve. Sockets work a bit like the header pins, but one end is a socket, the other a pin. You solder the pin end to the PCB, and then use thin wires to anchor the microcontroller to the socket. These need to be fairly firm. Standard practice, I gather, is to save the bits from the diodes. This took a bit more time than I though it would. Mostly because the soldering for the control board takes quite a bit more skill that I had when I started, so I messed up about 2 boards before I got the technique down. The key is to make sure that you push the wire all the way into the socket (use a good pair of tweezers or plyers for this).
[[image of socketing from Picture]]

## Switches
The microcontroller finished, I tested the board and moved on to soldering the switches. While this process was fairly easy, and took approximately 50 minutes, it also exposed some weaknesses with my soldering technique. Firstly, the keys on the top row stopped working because the socket headers had an error in the soldering. Fixing that was a bit tricky as I had the switches soldered at that point but I managed to not mess anything up too much.
Once the top row went live, I was still encountering random dead switches. These were again due to errors in the initial solder, but were a lot easier to fix.
# Finishing
The keyboard was the first part I started on the project and the first finished, as I was still working with the 3D models and printing. Rather than leave the board half finished I mounted up some keycaps and took a picture of the "assembled keyboard" to celebrate.
This is the keyboard kit on its own full assembled. I'll remove the bottom plate and install it into the case once it's printed.
[[image of completed keyboard]]
