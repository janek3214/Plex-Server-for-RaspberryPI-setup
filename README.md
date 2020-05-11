# Plex-Server-for-RaspberryPI-setup
Setting up Plex Server for RaspberryPI guide 



Setting up Plex Server for PI. 

Download Raspberry Pi Imager for specified OS that you are running from https://www.raspberrypi.org/downloads/

Install the application. 

Connect the MicroSD card and format it.

Install Raspbian to your card. 

Insert card to your Pi and wait for Raspbian to load and update required settings and updates. 




Usefull commands 

$sudo systemctl status plexmediaserver - Check status of server 

$sudo systemctl restart plexmediaserver - Restart server

If raspberry boots in command line only 

mount -o remount,rw /
