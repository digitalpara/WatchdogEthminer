﻿# Begin first windows mining tweaks then nvidia profil inspector then begin with mining Ethminer_Watchdog
Restarts Ethminer on Error in Logfile

__________________________________________________________________________________________

Copy all Files into Ethminer Folder.

Configure mining.cmd, watchdog.bat to your needs ( or just mine to my address :P )

start watchdog.bat

keypress in mining process:

"X": restarts on current pool, creates a new DAG

"R": restarts Batchfile, you can choose a new pool.


Tipps: set -v 1 to get smallest output ( speed is not shown in this minimalistic output, but corretly transfered to pool )

If you don´t like to download unknown executables (wintee), 
feel free to get it here : https://code.google.com/archive/p/wintee/downloads

__________________________________________________________________________________________

Enjoy

Tips: Eth 0x7F5BB53c415334235a9E42eA03695F11b6553C0Dchangelog:
1.6 : added correct stratum settings for ethermine.org ( see sample 5)
      you can now seamingless change between geth and stratum. ( stratum tested on ethermine.org )
      
1.7:  added colored output, stats (shares, time per session) - updates every minute. colors should only work on Windows 10 
      IMPORTANT: This release contains character hex1B, that is needed for the colored output, when editing, make sure you use a editor 
      which supports ANSI Char HEX 1B ( ESC character ) notepad++ does that for example.
