# filedialog
Open file dialog TUI for Terminals coded in Freepascal

TO COMPILE:  

    * Install Freepascal. Download or clone repository.
    * Type "fpc openfile.pas" to build.
    
These units use RTL (video and keyboard) for Text Mode. 

I've created this only for fun and to learn programming. That's why they are full of mistakes and redundancies.
I hope this will help me become a better programmer one day. 

Units:
======

Text mode: Compatible with video unit.

* aedcho2.pas >> Unit that creates a dynamic list to select different options.
* winvideo.pas >> Unit that allows to create dynamic windows.
* vidutil.pas >> Unit with tools to expand the video functionality.
* hex2bin.pas >> Unit to handle different operations with hexadecimals.

Programs:
=========
* openfile.pas >> Text mode ASCII table with windows and multiple choice using unit video.

In text mode:

![Alt text](optext.png?raw=true "Openfile dialog")

EOF
