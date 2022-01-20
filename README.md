# Win95 

## Win95 Versions

## Boot logo

LOGO.SYS is in fact an 8-bit RLE-encoded Windows bitmap file with a resolution of exactly 320×400 pixels at 256 colors. 


Replace the Ugly Startup and Shutdown Screens

Intended For
Windows Me
Windows 98
Windows 95
The pictures that tell you to "Please wait while Windows is shutting down" and that "It is now safe to turn off your computer" seem to get uglier with ever successive version of Windows. Here's how to replace these with your own designs:

    Make duplicates of the files LOGOS.SYS and LOGOW.SYS in a temporary folder. These files are located initially in your Windows folder. LOGOW.SYS is the one that reads "Please wait while...," and LOGOS.SYS is the one that reads "It is now safe to...,"
    These files are just standard bitmaps, so rename the extensions of these duplicates to .BMP.
    You can use any graphics editor to edit these files, such as MSPaint, Photoshop, or Paint Shop Pro.
    The files are 256-color windows bitmaps (RGB-encoded, but not RGB color), 320 x 400.
    Since the aspect ratio (width / height) of these files are not standard 4:3, like most computer screens, the bitmaps will appear vertically elongated.
    To make your new design conform to this aspect ratio, resize the bitmap to 534 x 400 while you're working on it. Make sure to resize them back to 320 x 400 when you're done.
    Save your changes, and rename the extensions of your new files back to .SYS.
    Last, copy the new files back into your Windows folder. It might be smart to back up your original files.

    While you're at it, you can create a startup screen as well (using the above method).
    Just call the file LOGO.SYS, and place it in the root directory of your boot drive (usually C:\). There's no file to replace here; the default logo, imbedded in IO.SYS, is used if no LOGO.SYS file is found. Note: If you're using disk compression, like Doublespace, you'll need to put the file in the original boot drive (sometimes H:\).
    
    
