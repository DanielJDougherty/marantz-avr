# marantz-avr
Marantz M-CR610 Receiver for SmartThings

Based on the Denon driver by Kristopher Kubicki.

* Changed the power on/off commands to use standby.
* Removed the 0.9 multiplier for volume, as the actual value seems to map to the expected volume.
* Temporarily limited the volume range to 0-30, as I was having issues with clumsy fingers and didn't want to blow up my speakers :)
* Added a hardcoded list of a few functions for test purposes - again, temporary if I can figure out how to get the device capabilities, but this makes the next input button to work.
* Removed bits that aren't relevant to this device for clarity (mainly for my own benefit)

Clearly this needs work, but it works on my device and may be useful.




