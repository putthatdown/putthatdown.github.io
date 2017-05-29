---
title:  "Step 4: Settings"
date:   2017-05-29 12:00
---

Up to this point, things have been pretty straight forward. Now its time to break out the keyboard and make basic configuration changes.

1. The HDMI cable should handle the video and audio. Go to the Audio settings in the RetroPie menu and select “HDMI” from the list of outputs.
2. If you’re not using wired Ethernet, go to “Wifi” in the RetroPie menu and connect to a Wi-Fi network. The Pi 3 natively supports 2.4GHz 802.11n, which isn’t great, but it’s fine for the price and good enough for our purposes.<br/><br/>Full disclosure, I haven't gotten wifi to work properly yet. It finds my network, but the Pi refuses to connect. Thus, the Ethernet cable. Not a huge inconvenience; once everything is loaded and configured, internet isn't really necessary.
3. Once you’re on the Internet, press F4 on the keyboard to access the command line
4. Take note of your box’s IP address, which will be displayed along with other system information.
5. Type `passwd` if you’d like to change the default account’s password for security purposes. The default username is `pi` and the default password is `raspberry`.
6. Type `sudo apt-get update` and then `sudo apt-get upgrade` to refresh the list of available packages and download and install those updates.
7. Type `sudo shutdown –r` to reboot the box once it's done updating

At this point, we've got the most basic configuration. In a future posts, we'll cover uploading ROMs, configuring controllers, customizing things, and eventually figuring out the wifi.
