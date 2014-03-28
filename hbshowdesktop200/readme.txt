Herwig's Show Desktop widget (Release 2.0.0)
============================================


1. What is this?

Pressing the button will minimize all windows and show the desktop.
Pressing the button once more will restore those windows that were
minimized last time. 

The tooltip shows which action the widget is going to perform upon 
the next mouse click.

Using a a modifier key (CTRL, ALT or SHIFT) with the mouse click will
always show the desktop no matter which windows were minimzed by the
last click.

2. Requirements:

- XWPS 0.9.11 or better
- Martin Lafaix widget library 0.5.0 or better
- VX-REXX runtime named VROBJ.DLL in your LIBPATH

3. Installation

	1. unzip the whole file in a temporary directory
	2. Make sure you have VROBJ.DLL in your LIBPATH. It can be found on the
	   original Warp 4 CD-ROM in case you do not have it.
	3. Move the files HBShowDesktop200 to your desktop 
	   (Attention! Make sure you did not loose the extended attributes!)
	4. ctrl-drag the HBShowDesktop200 widget to your xCenter
	5. READ ON BEFORE TRYING IT OUT!

The icon and the script as plain text file are included for manual installation
in case something goes wrong with the widget file.
	
4. Options and configuration:

As this widget minimizes all windows that are either maximized or normal,
there is the need to have an exception list, because otherwise even the 
desktop itself would get minimized, which is probably not desired...

I have predefined a few other objects that I don't want to have	minimized 
either. Feel free to add your own windows, that should not be minimized to 
the exception list.

Unfortunately, the desktop and other probably not-to-minimize windows
are named differently on every language flavor of OS/2. I have only
English (and German in comment brackets) names in the list.

SO, DO NOT FORGET TO ADD AT LEAST THE NAME OF YOUR DESKTOP TO THE LIST!

5. History and author:

The Show Desktop widget before release 2.0.0 came in 2 flavours:
As a RexxButton widget and a standalone .EXE file.

I have dropped the standalone .EXE file, because release 2.0.0 uses
specific RexxButton features. If you think you cannot live without the
.EXE file, drop me a mail and we could eventually make a deal...

10-08-2002
Herwig Bauernfeind
mailto: herwig.bauernfeind@aon.at
