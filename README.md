# crapulator
Automated raspberry pi setup for a box that can be used to inject network performance degradation at will. It is also built to act as a NAT gateway from a variety of devices such as a WLAN, cellular stick, or a USB-tethered cell.
1. Image raspbian stretch on a microSD card
2. edit WPA supplicant. copy wpa_supplicant.conf & ssh files onto the microSD before first boot.
3. boot, ssh to pi, sudo su, copy this script and run it
or from the shell just run:

`curl -sSL https://raw.github.com/rylatorr/crapulator/master/crapulator.sh | bash`


        
