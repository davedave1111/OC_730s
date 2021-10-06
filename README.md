# OC_730s
This is repository containing the Opencore configurations for launching OSX on a Lenovo Ideapad 730s

Current Project Status: WIP

I can't guarentee that this configuration will work for everyone, but this is what I have working so far on my Lenovo Ideapad 730s-13IWL

First, the specs of this laptop:


CPU:            Intel i7-8565U (Whiskey Lake)
GPU:            Intel UHD Graphics 620
Ram:            16 GB DDR4
Audio Codec:    Not sure yet, haven't started messing with audio
Wifi/BT:        Intel(R) Wireless-AC 9260 160MHz
Touchpad:       Synaptics 2393


Here's what is currently tested and working:

-Keyboard
-Touchpad w/ multitouch gestures
-Camera 
-Brightness controls (NOT the buttons)
-USB C ports 
-Wifi
-Bluetooth* (Kind of, see footnote)
-Battery Readouts
-iGPU

Here's what doesn't work:

-Sound 
-Bluetooth* (Again, see footnote)
-Fingerprint Sensor (As of right now, this will not work until someone figures a work around the TM chip in real macs)

Untested:
-Sidecar
-Airdrop

*Note about bluetooth* - It has trouble connecting to some devices, such as mice. Works perfectly with my airpods and generic bluetooth headphones though
*Note about boot* There appears to be a problem with the PNLF patch, and the backlight takes roughly a minute to turn on at first boot. I'm working of fixing it

Final note, this is a WIP, so yes, it's not perfect, and theres a LOT of bloat, it takes a while to boot. I will be fixing stuff slowly though and trying to make it the smoothest possible!


