unpack plist png
================

Let the large png file decompose into tiny png file with the use of plist and png files.

##Configuration:
  The script "unpack_plist.py" only work in windows environment. Before using it, you should :
  
  *1.install python2.7(make sure python is correspond to pillow, that means 32bit to 32bit.)
  *2.install Python Extension Packages Pillow‑2.6.1.win32‑py2.7.exe or Pillow‑2.6.1.win‑amd64‑py2.7.exe.
  
  here is download url: http://www.lfd.uci.edu/~gohlke/pythonlibs/#pil

##Usage:
  Put "unpack_plist.py" script file in the same directory with plist and png files.
  use the command:
  >python unpack_plist.py plistname
  
  then the folder name "plistname" will be made and it includes tiny png files you want.

##Example
  if the current directory has files "unpack_plist.py" "MessageImage.plist" and "MessageImage.png", the only work you should do is typing the follow command: python unpack_plist.py MessageImage. Then the tiny png files are made.
