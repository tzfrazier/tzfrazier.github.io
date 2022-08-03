---
layout: post
title:  Penkesu Computer Fork - Part 2: Flashing firmware
catagories: [blog, Projects]
tags: [July, 2022, July 2022, Computer Projects, Raspberry Pi, Obsidian]
date: 8th July, 2022
---
# Flashing the Keyboard Software
When you've soldered the diodes, the controller mount, and the microcontroller to the BCB, it's time to test the keyboard, and the first step is to flash firmware to the microcontroller. You should be able to do this pretty easily using QMK. You can run into several issues along the way, but I found it easiest to simply find the firmware package for the PCB, and use the defaults. I spent a lot of time developing a custom layout but realized I probably didn't need it, and could always go back later. My goal is the Penkesu, not a Plank 40% that perfectly met my typing needs.

# Firmware
 QMK is based mostly in C# I believe, so if your fluent; go, fight, win. Otherwise, it's relatively easy to o to the QMK firmware page and follow the documentation. Install the software then get ready to roll your firmware. I found following the ["building your first firmware"](https://docs.qmk.fm/#/newbs_building_firmware) page to be very easy to follow, though I did also bounce around in the documentation. The process for me was as follows:
1. Configure the build environment
2. Create keymap
3. Build firmware
4. Open QMK Toolbox and load firmware
5. Put Keyboard into boot models
6. Flash firmware to keyboard

# Important stuff
A few issues potentially arise at this point. Firstly, if you don't have experience reading documentation and working with computers you might get very frustrated at this point. At this point I've been a computer dabbler for nearly a decade and I'm just getting comfortable at reading documentation. If you get lost or upset, take a break. It's important to read the documentation relatively closely. I've found that even clear, well written documentation requires close reading, the first time you're trying something. The documentation for QMK is pretty good, but you have to spend some time with it. When I was working on grokking the firmware, I came across a helpful [post](https://vgpena.github.io/qmk/) that made me feel a bit better. Inspired I was able to go back to the documentation and figure out the firmware.

## Use The Right Cable
Putting the board into boot mode to flash the firmware is relatively easy as long as you have the right micro-usb cable, some cables provide charging only. When you've got the right cable in it should be easy to put into bootload mode. QMK toolbox, should recognize the board if your using the right cable, though it needs to be in boot mode to flash.
