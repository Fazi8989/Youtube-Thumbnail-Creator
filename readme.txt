WHAT THIS SCRIPT IS FOR:
For people that have a massive directory of images (ie 30,000+) and want to be able to randomly grab one and crop it into youtube dimensions (1260x720) at the click of a button.

BEFORE USE:
-Make sure all images are in a singular format (such as all jpg or png).  Free software I recommend is Bulk Image Converter from sourceforge.
-Number all images numerically (examples: 1.jpg to 50000.jpg) which can be done using the free software Bulk Rename Utility
-Ignore warning text on first usage of executable.

HOW TO MODIFY:
Change the selection of images: In the script where it says $((RANDOM%15779+1)), change the big number to the final image number (30000 if 300000.jpg) and 1 to whatever the first image number is.
Change the final product name of "cover" if you want.  Everytime you run it, the last cover will be deleted and replaced.


To create an executable version (of a bash script) for newcomers,

1) cd to the location of choice,
2) open nano
3) input script
4) save