# rpi-nodered-security
Monitor your security system with a Raspberry Pi and Node-Red

What you need:

A Security (alarm) System with 7 outputs available. I used a DSC 1864 with an 8 point output board.
A Raspberry Pi (I think any Pi will work, maybe not the Zero)
Your Pi connected to the internet.
A server running MySQL for the Pi to connect to. Optionally install MySQL on your Pi but that it not recommended.
I made a custom board to interface between the Pi and the security board. All this board did was contain resistors to protect the Pi's pins. It is not absolutely recquired. But highly recommended!.
(FYI: The stay feature wont work on DSC systems without some elboe grease)

visit http://itsalllost.com/monitor-your-security-system-with-a-rpi/ for more information.
