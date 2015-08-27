# HP_Stream_11

for wifi
1. Download https://github.com/lwfinger/rtlwifi_new 
2. Extract zip.
3. Open Terminal and cd to extracted folder. 
4. Type "sudo make"
5. Type "sudo make install"
6. Reboot

for trackpad
Copy the file /usr/share/X11/xorg.conf.d/50-synaptics.conf to /etc/X11/xorg.conf.d/50-synaptics.conf.

(I had to create the xord.conf.d folder under /etc/X11/ first)

Open the new file (under /etc/X11) and change the line “MatchDriver “synaptics”” with “Option “ClickPad” “on”” and the line “Option “SoftButtonAreas” “50% 0 82% 0 0 0 0 0” to “Option “SoftButtonAreas” “50% 0 50% 0 0 0 0 0”.
