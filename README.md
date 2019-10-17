# MagicMirror-Win10V2
1. Install node.js from the following link:
	https://nodejs.org/en/download/

2. Install Git for Windows from the following link:
	https://gitforwindows.org/

3. Download a .zip file of the MagicMirror source:
	https://github.com/MichMich/MagicMirror
   Press green "Clone or download" button to get option for zip download

4. Open the zip file, and copy the MagicMirror-master folder to C:\Users\YOURUSER

5. Rename that folder to just "MagicMirror", so remove the "-master"

6. Open Git Bash (installed with Git for Windows)

7. Execute following commands:
	cd MagicMirror
	npm install

8. Close Git Bash

9. Open C:\Users\YOURUSER\MagicMirror\config

10. Copy "config.js.sample" and paste it in the same folder

11. Rename the copy to just be "config.js" and accept the Windows warning about renaming files

12. Open config.js with a text editor (Notepad++ is a good option)
	Add the following line below the "units" line while keeping the formatting:
	electronOptions: { fullscreen: false, width: 800, height: 600 },

13. Save config.js and close it

14. Open Git Bash

15. Execute following commands:
	cd MagicMirror
	npm start

Congrats, you should have a running version of MagicMirror on your windows machine. You can now customize
that config file to add in modules or remove them. A tutorial for such is in the MagicMirror website/forums.

NOTES: 
1. Some modules will NOT work by default if they require Linux-specific information. (Ex: System Stats modules,
looks for Linux system stats info)

2. Press the Alt key to open the top bar in the application. This is how you exit MagicMirror

3. Step # changes how MagicMirror appears when it starts. When using, start the application, move the window to the
monitor that you want it on, then hit F11 to make it full screen. If you want MagicMirror to start with different 
dimensions, just change the ones that are in this tutorial.

LINKS:
Following link helped me out a little bit when I made this process. Used some of their methods to simplify process
	https://forum.magicmirror.builders/topic/4089/complete-walkthrough-install-magicmirror-on-a-pc-windows-7-10/2
