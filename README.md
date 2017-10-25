Directions
==========
1) put songupdater.txt on your desktop and open runscript.wflow
2) in the runscript.wflow workflow scroll down in the "Run AppleScript" tab
3) replace: ("/users/user/Desktop/") & "songupdater.txt" with ("/path/to/your/desktop") & "songupdater.txt"
4) click run at the top of the workflow to begin posting your song info to the text file
5) the current iTunes song will we written in songupdater.txt on your desktop every 10 seconds.
6) in OBS or whatever stream software you use, select add text source and select "songupdater.txt" from the list.
6) you now have your current iTunes song on your stream.

Additional info
===============
The workflow will run for 16 hours straight. If your stream is somehow longer than that, you will have to restart the workflow around the 16 hour mark. 
This is the maximum allowed time for the workflow unfortunately. Enjoy!
