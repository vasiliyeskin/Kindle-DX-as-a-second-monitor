# Kindle-DX-as-second-monitor

This method tests on the Windows 10.

The instruction was made on the base of the following descriptions:
[https://www.pcworld.com/article/259582/how_to_use_a_kindle_dx_as_a_pc_display.html](https://www.pcworld.com/article/259582/how_to_use_a_kindle_dx_as_a_pc_display.html)
[https://www.youtube.com/watch?v=tQQvQx2ep1o](https://www.youtube.com/watch?v=tQQvQx2ep1o)
[https://www.mobileread.com/forums/showthread.php?t=204942](https://www.mobileread.com/forums/showthread.php?t=204942)
[https://www.youtube.com/watch?v=7ecuTxcHwgE](https://www.youtube.com/watch?v=7ecuTxcHwgE)
[https://www.youtube.com/watch?v=8UFjgSQe-nU](https://www.youtube.com/watch?v=8UFjgSQe-nU)
[https://forum.moddevices.com/t/rndis-driver-for-windows-10/299](https://forum.moddevices.com/t/rndis-driver-for-windows-10/299)

Main instructions are there
[https://www.youtube.com/watch?v=7ecuTxcHwgE](https://www.youtube.com/watch?v=7ecuTxcHwgE)
[https://www.youtube.com/watch?v=8UFjgSQe-nU](https://www.youtube.com/watch?v=8UFjgSQe-nU)

## 1. Install in the following order (from the "VNC Viewer for Kindle Full Pack - Win 7 32 bit.zip")

### Jailbreak
### Launchpad
### USBnetwork

You must install it from the menu "Update your Kindle" on the menu.

## 2. Copy "Kindle VNC" to the Kindle root.
For DX it is need to remove line "set_k3_keycodes()" in "kindlevncviewer\config.lua".
Delete default password 111111 in "launchpad\kindlevncviewer.ini".

## 3. Disconnect USB cable. 
Press quickly "Shift Shift Spacebar" for the restarting Launchpad.
Press quickly "Shift N" for a switch on the USB network. It is appearing "Success!"

## 4. Connect the USB cable.
Windows installs a new device. If not you must install RNDIS driver.

## 5. In the settings of new network change IP 192.168.2.1 with mask 255.255.255.0

## 6. Install TightVNC ([https://www.tightvnc.com/download.php](https://www.tightvnc.com/download.php))
Launch TightVNC. Main server 5901.

## 7. Press Win+P, change "Extend", then go to "Display Setting"
Do it the second monitor as a left monitor: drag monitor 2 to the left.

## 8. What do you must do for the use?
0. Run TightVNC server.
1. Put Kindle in the Landscape mode: press button "Aa" and choice.
2. Press quickly "Shift N".
3. Connect Kindle with the USB cable to the computer.
4. Press Win+P, change "Extend" and display resolution.
5. Press quickly "Shift V U". Enjoy it!
6. For the ending press "Home" on the Kindle and quickly "Shift N".