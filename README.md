# ubuntu-low-mem-popup
Script to show a popup message when your machine is low on memory

This is cloned & modified script from https://askubuntu.com/questions/234292/warning-when-available-ram-approaches-zero

It also add's details on top 3 memory-hungry processes

The purpose for this is when there is low memory on host machine and the system starts swapping then a huge lag occurs (at least on SSD disk)

I'm using KDE Plasma autostart settings to start this script at startup
To make it work with cron, refer to https://anmolsinghjaggi.wordpress.com/2016/05/11/notify-send-in-ubuntu-16-lts/

