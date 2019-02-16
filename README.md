# cursor-track

cursor-track is a utility that is intended to allow you to press a keyboard shortcut to activate a cursor tracking animted gif that will follow your cursor around the screen until you click.

## Dependencies

  * python3
  * qt5

## Usage

Make cursor-track.py executable.  Change #!/usr/bin/python3 if necessary.  You can create your own animated gif with gimp.  Just make sure you replace the 100x100 dimensions in the code to match the size of the image you create.

Use your system keyboard shortcut feature to activate script on demand.  I used Ctrl-Shift-F.

Tested only on xfce4 Ubuntu 18.04

** Note: In multi-head environments, this will only track your mouse on the screen the pointer was on when you activate the shortcut keys.

### TODO:
  * get size of image instead of hardcoded 100x100
  * optionally draw concentric circles with qt5 
  * fix multi-head display
