---
title:  "Step 2: RetroPie"
date:   2017-05-26 15:00
---

Raspberry Pi hardware doesn't come with any kind of memory or BIOS, this section will cover the steps required to load RetroPie on a micro SD card.

Fortunately, video game emulation has been around for a while, so there are a number of well packaged options available. We're going to use RetroPie as our base, which is well supported, well documented, and customizable. It also includes a huge number of emulators, so even though my focus is on the NES, it'll be possible to expand it out in the future.

I used the following steps on a MacBook w/Sierra to prepare the SD card:

1. Download the [latest Raspberry Pi 2/3 RetroPie image](https://retropie.org.uk/download/)
2. Download [ApplePi-Baker for Mac OSX](https://www.tweaking4all.com/software/macosx-software/macosx-apple-pi-baker/)
3. Decompress the .gz file you downloaded from the RetroPie site
4. Plug your SD card into the Mac
5. Open ApplePi-Baker
6. Select your SD card in the Pie Crust field (left)
7. Click [Prep for NOOBS] to format the SD card
8. Once the card is formatted, browse to your RetroPie .img file
9. Click [Restore Backup]
10. Once the process is complete, eject the card from the computer and put it into the RetroPie