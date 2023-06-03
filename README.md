# X11-Window-To-Monitor-Script
Bash script to move a window to a different monitor.

This was created for XFCE to simulate Gnome's WINDOWS+SHIFT+LEFT|RIGHT window moving. There is another script floating around that this was based on, but wasn't as flexible as this. There was also an issue with some applications, such as VLC. The relative position wasn't being considered in thsi applications placement, so an exception was made. This keeps the window at the same position across monitors. I have not tested this with monitors with different resolutions, which will probably not work correctly.

Dependencies
wmctrl xdotool
Debian : sudo apt install wmctrl xdotool -y

Usage
bash movemonitor DIRECTION
direction:
   previous (move window to the previous monitor)
   next (move window to the next monitor)
