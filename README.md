# Rasp_AdventisementsShow
This script will transform the Raspberry Pi 3B+ in an advertisement screen.
Some video examples to launch are in the .zip file

Instructions:

At first install the video player:
~~~~
sudo apt-get install omxplayer
~~~~

Then try the bash script in terminal:
~~~~
./videoplayer.sh
~~~~

To autostart the bash script on Raspberry boot, do as following:
~~~~
sudo nano /etc/xdg/lxsession/LXDE-pi/autostart
~~~~
and add at the bottom line:
~~~~
@bash /home/pi/pub.sh &
~~~~
