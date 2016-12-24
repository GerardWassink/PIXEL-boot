# raspi-reboot

A script to determine the way your PIXEL OS will boot next time.

This script must be executed as root (use the sudo command).

This script intended for PIXEL implementations on other machines than the Raspberry Pi 
because raspi-config is as of yet not available in that	distribution. 

I could not get option 2 to work, so I commented it out.

I stripped parts out of raspi-config https://github.com/RPi-Distro/raspi-config, just for setting desired boot option:

1. Text console, requiring user to login

2. Text console, automatically logged in as pi user (not implemented, see above)

3. Desktop GUI, requiring user to login

4. Desktop GUI, automatically logged in as pi user

