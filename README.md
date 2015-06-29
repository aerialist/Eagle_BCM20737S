# Eagle_BCM20737S
Eagle library for BCM20737S, Bluetooth Low Energy SiP from Broadcom

Warning! There can be fatal mistakes.
This library has not been tested in production. 

Tried to copy solder pad dimensions from iBeacon BCM20737S Reference Design Gerber Files (Module) by Broadcom
http://community.broadcom.com/docs/DOC-1591

Tried to mimic the symbol from iBeacon BCM20737S Reference Design PDF Schematic (Module) by Broadcom
http://community.broadcom.com/docs/DOC-1577

Pysical package outline and GND keep out area dimensions were taken from the datasheet, BCM20737S Bluetooth Low Energy SiP Module Technical Reference, 20737S-DS100-R.pdf
http://community.broadcom.com/docs/DOC-1737

I gave up taking solder pad dimensions from datasheet as there are too many ambiguity.
Take Type C pad dimension for example, Table 12 reads its "Pad dimensions" are 0.4 x 0.4 and "Solder Mask Opening Dimension" is 0.5 x 0.5.
Then Figure 9 Stensil reads it 0.35 x 0.35 while Figure 14 Package Dimensions reads b1: 0.35.
Which number should I use as dimension of solder pad??

