MPD_Tray
========

Python tray icon for controlling music player daemon (MPD) servers via mpc commands, with tooltip display of current song.

Executing the script places an icon in the taskbar, which displays the current song playing on MPD upon cursor hover. 

While hovering over the tray icon:
mouse wheel controls MPD volume (if volume mixer is set as software in the MPD config)
single click pauses/plays
middle click plays the next track
right click brings up a menu to select the next or previous track.

Dependencies: mpc

This script was mostly based on the script described in this blog from 2006: http://blog.natulte.net/posts/2006-09-26-a-really-good-radio-and-a-really-cool-python-script.html. Much credit to David Anderson, whereever you are.
