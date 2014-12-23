SHARC assembly Sublime Syntax
=============================

A syntax definition for the SHARC's (The DSP board from Analog Devices) assembly language. I think it works reasonably well. As far as I know, no other ones exist. It does *not* include keywords for Analog Devices' TigerSHARC board, and the Blackfin definitions are not very well researched. I spent the semester with a SHARC board, so there you go.

I made this because I really don't like the VisualDSP++ IDE that much. No word wrap, tabs, etc...

Installation (Windows):
- Get sublime_text.
- Install "Package Control" : https://sublime.wbond.net/installation#st2
- Extract/copy/Whatever-I-Don't-Care "Assembly x86 AT&T.tmLanguage" and "Comments (ASM x86).tmPreferences" into [sublime directory]\Data\Packages\User\
- Or simply `git clone' this repo.
- I'm currently attempting to move this to Package control, so sit tight.

Pull requests and bug reports always welcome.

Sublime should automatically take care of the syntax highlighting, so there's no need to restart.


Description of Files:
- blahblah.JSON-tmLanguage : the syntax definition in JSON form. More convenient to edit, but must be converted first. Press F7 after installing AAApackagedev.
- blahblah.tmLanguage : the syntax definition in tmLanguage form (a form of xml). Can be edited directly without compiling.
- blahblah.tmPreferences : enables the commenting shortcut of sublime text.
- README.md : read this file from the top for more information.
