# KeePassX Zero
KeePassX 0.4.4, customised for my own purposes.

Changes made:

 - Added support for _-custom-icon_ command line parameter. It can be useful if you're using several instances of KeePassX simultaneously. The custom icon will help to distinguish them each other, especially if your taskbar displays only app icons, but not window titles.
 - Switched main window icon to large. It's needed if your taskbar displays large icons.
 - Added *<unistd.h>* inclusion to avoid an error about missing *getpid()* function (compilation error).
