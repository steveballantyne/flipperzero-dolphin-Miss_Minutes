#!/bin/shebangs.shemoves

# flipperzero-dolphin-Miss_Minutes
# Miss Minutes as a Dolphin Animation for the Flipper Zero

LAB401 does an *awesome* (not to mention, entertaining) how-to on custom animations for the Flipper Zero. I highly
recommend it as a primer of how animations work and how to install them.

WATCH-ME: https://www.youtube.com/watch?v=Nq5DXhOMo5s

With the Flipper's dank orange display, it seemed absolutely necessary to do a Miss Minutes animation. In fact, I am
thinking that an entire TVA Tempad theme is in order!

TO INSTALL:
1) Grab all the files (you don't even have to know how Git works, just click the Code dropdown and select Download Zip.
2) Open qflipper and click the "documents" (File Browser) icon.
3) Browse to SD Card > Dolphin.
4) Right-click somewhere and select New Folder. Name it "Miss_Minutes_128x64".
5) Open this new empty folder. Right-Click and choose "Uplaod here ..."
6) Browse to and upload all of the files ending in ".bm" and also the meta.txt file.
7) UPDATE YOUR MANIFEST! - See below ...

HOW TO UPDATE YOUR MANIFEST:
The manfifest is a list of all of the animations on your flipper. It also dictates how often that they should run. You
probably want to KEEP your other fun animations. So you should EDIT your Manifest file, and then only ADD the last
cluster of text from the included Manifest.txt to your own Manifest.txt.

1) Open qflipper and browse to: SD Card > dolphin.
2) Right-click "Manifest.txt" and Download it.
3) Open Manifest.txt with your favorite text editor. Scroll to the bottom. Then add the following:

Name: Miss_Minutes_128x64

Min butthurt: 0

Max butthurt: 12

Min level: 1

Max level: 3

Weight: 8


4) Note that the WEIGHT is how often you want the animation to play. 1 is very seldom, 8 is often. If this is the ONLY animation in your list, it's the only thing that will play.

IMPORTANT NOTE: DO NOT DELETE the top part of this file, which includes something like this:

Filetype: Flipper Animation Manifest
Version: 1

5) Save your modified Manifest.txt file.
6) In qflipper, right click and choose "Upload File...".
7) Browser to and select your modified Manifest.txt file and replace your current one.
8) WAIT. If you want to see this animation RIGHT AWAY, you will need to make this the only animation in your Manifest.txt file, and then reboot

HAVE FUN.
