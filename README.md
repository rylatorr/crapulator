# ghettoCradle
Automated raspberry pi setup for a specific use-case
1) Image raspbian stretch on a microSD card 
2) edit WPA supplicant. copy wpa_supplicant.conf & ssh files onto the microSD before first boot. 
3) boot, ssh to pi, copy the script to the pi and run it as root (sudo su) or curl -sSL https://raw.github.com/rylatorr/ghettoCradle/master/ghettocradle.sh | bash
        
