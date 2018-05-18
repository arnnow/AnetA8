# RepRap Wiki for AnetA8 
* https://3dprint.wiki/reprap/anet/a8

# Printing Process 
https://www.propwashed.com/anet-a8-build-guide-and-1st-print/

## Leveling The Bed :

1.  Power up your printer and access the main menu.  
2.  Heat the bed and extruder to PLA settings by going to Quick Settings->Preheat PLA. Do not touch the extruder tip after completing this step! It will be extremely hot. The bed will also be hot, but touchable.  
3.  Go to Quick Settings->Home All. The printer head should move to all the limit switches.  
4.  Disable the motors by going to Quick Settings->Disable Stepper Motor.  
5.  Move the printer head along the X-axis and bed along the Y-axis so that it is over the close-left corner of the bed relative to you.  
6.  Adjust the printer bed screw until you can just fit a piece of card stock paper (measuring .2mm in width) between the bed and the extruder tip. You want the tip to be hitting the cardstock but not pressing it into the bed. You can test this by moving the head with the card under the tip. If the card moves with the head, that’s great. You don’t want it to be hard to move or for it to make scratching noises while it drags on the paper though. You should be able to insert and remove the card easily.  
7.  Repeat (4) and (5) for the other 3 corners of the printer bed.  
8.  Repeat the whole process again, noting any errors.  
9.  If any adjustments were made in step (7), repeat the process again. Keep repeating it until you check all four corners with no errors found at all.  
10. Screw on and tighten the wing nuts which secure the bed leveling mechanism.  
11. Repeat the leveling process one more time – sometimes the wing nuts can throw it off.  


## The process of printing a gcode file is a few easy steps:

1.   Put the file on the root of your SD card.  
2.  Insert the SD card into your Anet A8 printer.  
3.  Access the main menu by pressing the center button and select “SD Card->Mount”.  
4.  Access “Print File”.  
5.  Select the gcode file you wish to print.  

# Anet A8 improvment :

## Firmware 
* [Firmware](firmware/README.md)

## Communicate with the printer board
https://github.com/kliment/Printrun/blob/master/README.md  
https://www.youtube.com/watch?v=R1VugOTOoGA

## AutoBedLeveling - BLTouch
https://www.youtube.com/watch?v=WWDkZtWwd6I&index=1&list=PLlcMt_sdtxsCmJl5oZLiO3Ub6LN2GBwIe  

## Z Wobble 
correct installation:  https://www.youtube.com/watch?v=T9vI6DqAcmo  

## Frame brace for 3D printer Anet A8
This part distribute pressure on the front acrylic part surface and minimise wobbling on Y axis.  
https://www.youtube.com/watch?v=lH3gHLyIiec  
https://www.thingiverse.com/thing:1430727  

## Cable Chain
search Cable chain anet a8 on thingiverse

## mosfet 
https://3dprint.wiki/reprap/electronics/heatbed_mosfet  

## alimentation:
PSU 12V 30A 360W  
https://best3dprinter.stan-tech.com/anet-a8-power-supply-adding-a-mains-socket  
https://www.youtube.com/watch?v=KrB72XIm2_E  
ATX PowerSuply :   
https://www.youtube.com/watch?v=SBhlHQbUaqs  
https://www.youtube.com/watch?v=JSNngyl1ONM  

## ventilation extruder
https://www.youtube.com/watch?v=09zWjMFJwT0  
https://www.thingiverse.com/make:427275  

## IKEA Lack Enclosure

# Control from web interface with rasberry
https://octoprint.org/  

# to print: 
https://www.thingiverse.com/thing:275091  


