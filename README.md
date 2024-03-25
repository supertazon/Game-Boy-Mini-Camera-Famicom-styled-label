# Game Boy Mini Camera Famicom styled label
For educational purposes only

<img src='https://github.com/supertazon/Game-Boy-Mini-Camera-Famicom-styled-label/assets/1402795/257b005a-bf3c-4894-b993-74edd415b4e3' width='500'>
<img src='https://github.com/supertazon/Game-Boy-Mini-Camera-Famicom-styled-label/assets/1402795/5e256dff-9416-4a21-ae76-ca13dbac1a5c' height='375'>

## What's in this repo and how to order

Included in this repo are two versions of the same label, both with two file formats: PDF ready to be sent to a print house and SVG for editing (with [Inkscape](https://inkscape.org/) for example - there are multiple layers in the SVG file for easier editing).
  1. White as a background version "-white": while discussing with different print shops, I discovered that for the white letters (MINI CAM and DMG-GBD) some could not print white ink on black ink but would rather print a white background then black ink on top leaving out the black ink to form the letters (a bit like a stencil). This version should work off the bat with all print houses however the SVG file is trickier to modify
  2. Standard version "-standard": the letters are shapes filled with white. Should also not be a problem for printing and much easier to edit the SVG file

I am based in France and couldn't find a suitable print shop in Europe for the labels. I had them printed through [Jukebox](https://www.jukeboxprint.com/custom-gold-stickers) (Canada):
  - Matte gold
  - Sticker dimensions are 42 x 37 mm (which looks a tiny bit too small IMO, see picture above)
  - Ask for the yellow background to be considered as the gold sticker

## Inspiration and process

Inspiration comes from the [14 Famicom Pulse Line cartridges](https://famicomworld.com/workshop/articles/pulse-line-cartridges/) that were sold in the early days of the Famicom. Their design is very sleek. I wanted to build a Famicom-styled Game Boy Mini Camera ever since Chris had shown the first pictures of his project. While finishing the build I thought a nice golden sticker would fit the design perfectly. I looked for scans of these labels and found [Arcanthur's collection of Famicom recreated labels](https://forums.launchbox-app.com/files/file/3676-nintendo-famicom-2d-carts-arcdragon/). I used them for reference, here is the label for Gomoku Narabe for example:

<img src='https://github.com/supertazon/Game-Boy-Mini-Camera-Famicom-styled-label/assets/1402795/37d3d0ca-35d0-45c7-ab3d-004356b8d10d' width='500'>

I then had to recreate the different parts of the labels to fit my needs, and did it using Inkscape:
  - **The black lines representing the Famicom Pulse Line**: I manually traced them using Inkscape and the pen tool
  - **The white letters of the English name of the cartridge**: provided the limited space I had, I settled for MINI CAM. I manually traced each letter from one of the 14 games, using the rectangle tool from Inkscape and applying rounded corners:
      - "M" (first) and "A" come from the MARIO BROS. label
      - "I" and "N" come from the TENNIS label
      - "C" comes from the "G" of the GOLF label that I later modified
      - "M" (last) comes from a modified "N" that I then mirrored
  - **The different text elements in latin alphabet**: I wanted to be as close as possible to the real deal and used [WhatFontIs](https://www.whatfontis.com) to detect which font was used in the Famicom Pulse Line labels, this is what I found:
      - "Audiovisual": Nirmala UI Semilight font (directly available on Windows 11)
      - "©": couldn't find a suitable font so I manually traced it as well
      - "Nintendo": I imported the [SVG from Wikipedia](https://upload.wikimedia.org/wikipedia/commons/b/b3/Nintendo_red_logo.svg)
      - "1998": corresponds to the release date of the Game Boy Camera - [HomepageBaukasten Book font](https://www.ffonts.net/HomepageBaukasten-Book1.font?text=1983)
      - "MADE IN JAPAN": [HomepageBaukasten Bold font](https://www.ffonts.net/HomepageBaukasten-Bold1.font?text=MADE%20IN%20JAPAN)
      - "DMG-GBD": I wanted to keep the same nomenclature as in the Famicom labels that have "HVC-XX" with "XX" the game code and "HVC" corresponding to the Famicom console. I thus settled on "DMG-GBD" with "DMG" corresponding to the first Game Boy and "GBD" to the [Game Boy Camera chip](https://niwanetwork.org/wiki/GBD_(Game_Boy_mapper)) - [HomepageBaukasten Bold font](https://www.ffonts.net/HomepageBaukasten-Bold1.font?text=DMG-GBD)
  - **The two Japanese text elements**:
      - Right of "DMG-GBD": On the Famicom labels it says ファミリーコンピュータ (Famirī Konpyūta - Family Computer), I naturally changed it to ゲームボーイ (Gēmu Bōi - Game Boy). However, finding the right font was tough, and only thanks to [Fontendo](https://twitter.com/Fontendou/status/1511150166207778817) did I manage to find the [System-N font](https://fontsinuse.com/typefaces/218628/system-n) which is an old recreation of the original font. To get these letters: ゲームボーイ, you have to input ":N]-Ne". The ボ ideogram was missing two small signs that I added on Inkscape
      - Main Japanese cartridge name: Provided the limited space I had, I used Google Translate to translate Mini Camera and it gave me ミニカメラ (Mini kamera). I looked around for a resembling font and used the [MOBO font](https://fontmeme.com/fonts/mobo-font/)
   
## Acknowledgments
  - Thanks to Nintendo and their engineers for all these years of incredible fun
  - [Christopher Graves](https://gameboycamera.com/) for their awesome [Game Boy Mini Camera project](https://gameboycamera.super.site/projects/game-boy-mini-camera)
  - [b_2_3_n](https://b_2_3_n.mmm.page/) for general advice

