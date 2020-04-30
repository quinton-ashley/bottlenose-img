# nostlan-img

Want to contribute to the open box menu of Nostlan (a frontend for emulators)? Help me out by taking photos of open game boxes, memory cards, and system safety/promotional manuals for use in the open box menus of the emulator frontend app, [Nostlan](https://github.com/quinton-ashley/nostlan).

| sys     | %    | images needed |
| ------- | ---- | ------------- |
| 3ds     | 0%   | all           |
| ds      | 100% |               |
| gba     | 100% |               |
| gcn     | 100% |               |
| ps2     | 75%  | manual        |
| ps3     | 0%   | all           |
| snes    | 100% |               |
| switch  | 75%  | manual        |
| wii     | 75%  | manual        |
| wiiu    | 100% |               |
| xbox360 | 100% |               |

I have no 3ds or ps3 game boxes, manuals, memory cards, etc. and will not be able to make the open box menu support these system on my own without these assets. Game collectors, please help me out here! You can just send photos and I'll edit them. I've put instructions on how I've been editing them if you want to do it yourself though. Before contributing to this repo please take a look at the assets I did as examples.

# Why are you doing this?

One of the goals of the Nostlan emulator front end project is to create a physical object based UI for archival and nostalgic purposes. The open box menu will look like this:

![gcn open box](https://raw.githubusercontent.com/quinton-ashley/nostlan-screenshots/master/gcn_open_box.png)

# Taking Photos

If you only have a smart phone you can still contribute to this project but you must use the Adobe Lightroom app and shoot in Pro mode using the raw .DNG filetype. Photos taken with the default iPhone camera app are compressed in size, reducing image quality and resolution, they don't capture what the sensor is capable of. I used an iPhone 6s Plus. If you have a nice DSLR or large format analog camera that'd be even better of course. I used a desktop light with a white bulb and daylight, don't use a yellow/orange light source. Shoot from the center of the item, laying it out as flat as possible. Try to avoid reflections.

## Highly Reflective Items (such as game discs)

If the item is highly reflective, you can try taking two pictures on a tripod and moving your light source so reflections occur on opposite sides. The reflections can then be edited out by combining the photos.

# Editing

## Manuals and Memory Cards

Simply add a transparency layer and erase the background.

![ds system manual](https://raw.githubusercontent.com/quinton-ashley/nostlan-img/master/ds/_TEMPLATE/img/manual0.png)

## Open Game Boxes

To get the edges of the game box to be artificially straight I used photoshop's perspective warp tool. Place rectangles over each section of the box, you can then warp those points to sit perfectly straight with the edges of the image.

![ds open box](https://raw.githubusercontent.com/quinton-ashley/nostlan-img/master/ds/_TEMPLATE/img/boxOpen.png)

## Open Game Box Mask

Cut out clips and slots that should appear in front of game media and manuals.

![ds open box mask](https://raw.githubusercontent.com/quinton-ashley/nostlan-img/master/ds/_TEMPLATE/img/boxOpenMask.png)

## Highly Reflective Items

Align the two images you took so that they match perfectly. Cross-fade between the sides with no reflections. The result should look seamless.

![ttyd disc](https://raw.githubusercontent.com/quinton-ashley/nostlan-gcn/master/gcn/G8ME01/img/disc.png)

# Submissions

Please send me <mailto:qashto@gmail.com> your original photos in lossless quality (.dng) and if you made edits, send me the photoshop/gimp files via google docs, dropbox, etc.

# Public Domain License CC0

The photos in this repository are public domain. Any photos submitted to me for use in this repository will be public domain. Do not submit photos to this repository if you wish to reserve your copyrights to the photos you submit.

## Legal Disclaimer

Although [Emulation is legal](https://en.wikipedia.org/wiki/Bleem!), pirating games you do not own is illegal. Nostlan does not condone piracy. Nostlan is open source software that does not infringe on any copyrights of texture packers, developers, or publishers. Nostlan is not affiliated with Nintendo, Sony, or Microsoft. Anyone asking for or sharing information related to digital piracy on this project's Github issues will have their comments removed and flagged.

## COPYRIGHT AND TRADEMARK INFO

MAME and the MAME Logo are Copyright © 1997-2019 MAMEDev and contributors. MAME® is a registered trademark of Gregory Ember. Use of the MAME name and logo is done so with the expressed written permission from the trademark owner. For more information, please visit <https://www.mamedev.org>.

Nostlan and the Nostlan logo images are Copyright © 2019 Quinton Ashley. The Nostlan logo images are licensed under [Attribution-NonCommercial-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-nc-sa/4.0/). The template images found in the [nostlan-img repository](https://github.com/quinton-ashley/nostlan-img) are public domain images using the Public Domain License CC0. The Nostlan software itself is fully open source and licensed under the copyleft [GNU GPLv3 license](https://en.wikipedia.org/wiki/GNU_General_Public_License).

Do you want the photoshop files of these images? Send me an email to request them: <qashto@gmail.com>
