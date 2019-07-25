# Rasp_AdventisementsShow
This script will transform the Raspberry Pi 3B+ in an advertisement screen.

To autostart the bash script on Raspberry autostart, do as following:

~~~~
sudo nano /etc/xdg/lxsession/LXDE-pi/autostart
~~~~

Add at the bottom the line:

~~~~
@bash /home/pi/pub.sh &
~~~~
