---
layout: post
title:  Penkesu Computer Fork - Part 1: Soldering
catagories: [blog, Projects]
tags: [July, 2022, July 2022, Computer Projects, Raspberry Pi, Obsidian]
date: 7th July, 2022
---
# 3D Modeling
The Penkesu is designed around Koda Keyboard. I poked around online and wasn't able to purchase a PCB. It looked like it would take more trouble to get a printed circuit board (hence, PCB) cut than to purchase a similar sized board, and I was able to find the Pancake from [MKUltra](https://mkultra.click/pancake-keyboard-kit), However, the keyboard PCB is slightly different in terms of dimensions even if the layout is the same. As a result I had to adjust the case model to fit the Pancake's PCB, and hence the need to for the project as, Pancakesu.  
[[Image of keyboard not fitting in case]]
# Software
Because the STL files are complex, it was difficult to use Tinkercad to alter the files. If you're doing most 3D modeling Tinkercad is good enough. Blender was too much, and those free options off the table, I went with SketchUp which has good balance between ease of use and power. I was able to get the dimensions of the pancake and easily resize the models, although I ran into a few additional issues I'll cover in more depth below.
[[screenshots]]
## Resizing
One thing I really appreciated about SketchUp after working with Tinkercad and Blender was the easy of selecting geometries or the lines and points that make up the model. 3D graphics programs and models tend rely on vectors, rather than pixels, so being able to select things easily was a huge boost. The move function and ruler function both made it trivial after a few goes to resize the case to fit a Pancake rather than Koda PCB.
## Other Adjustments
### Heat Instert Ankers
Both the original design and the design of the Pankcake PCB left me with the suggestion that I add, and adjust anker points so that I could add heat inserts and screw the keyboard into the case. Again Sketch up made it really  easy for me to add these by drawing a circle and subtracting it from the sides, or adding two circles and subtracting the middle from the larger one. [[?]] Looking at the power supply and the power supply and the Raspberry Pi Zero, I also added in mount points to make the build more secure.
### Power Switch
I bought a [cool on-off switch](https://www.adafruit.com/product/917) for this project, however, my experience tinkering with the models showed me that I wouldn't be able to use it, so I was able to find a switch in left over kit parts in [the maker space]() I was working out of. However, I still need to make a slight adjustment to accommodate difference. I used a similar technique to adjusting the case to fit. Setting guides, isolating the geometry, and moving them to adjust the model.  
# Rethinking the design
If I was designing from scratch I think Tinkercad would be sufficient and I would design it in part around the power switch
