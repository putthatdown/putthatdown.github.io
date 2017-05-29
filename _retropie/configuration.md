---
title:  "Configuration"
date:   2017-05-29 18:00
---

Up to this point, things have been pretty straight forward. Now its time to break out the keyboard and make basic configuration changes.

* The HDMI cable should handle the video and audio. Go to the Audio settings in the RetroPie menu and select “HDMI” from the list of outputs.
* If you’re not using wired Ethernet, go to “Wifi” in the RetroPie menu and connect to a Wi-Fi network. The Pi 3 natively supports 2.4GHz 802.11n, which isn’t great, but it’s fine for the price and good enough for our purposes.

Full disclosure, I haven't gotten this to work properly yet. It finds my network w/out issue, but refuses to connect, which is why I went with the Ethernet cable instead.
* Once you’re on the Internet, access the command line by pressing F4 on your keyboard or by pressing Start on the gamepad, selecting Quit, and then quitting EmulationStation.
* Take note of your box’s IP address, which will be displayed along with other system information.
Type passwd if you’d like to change the default account’s password for security purposes. The default username is pi and the default password is raspberry.
Type sudo apt-get update and then sudo apt-get upgrade. The first command refreshes the list of available packages from the device’s repositories, while the second actually downloads and installs those updates. Go ahead and install all updates when prompted.
Once it’s set up, our RetroPie box will be pretty appliance-like; you could disconnect it from your network and never worry about updating it again if you wanted. But new versions of both Raspbian and RetroPie are released periodically, and if you intend to keep the RetroPie box on your network permanently, you should at least install updates periodically.
Type sudo shutdown –r now to reboot your box, which will bring it back into the EmulationStation UI.