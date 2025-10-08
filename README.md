# What is this
This repo is a collection of ready to use, prewired parts of PCB designs you can use inside MCPU applications

## How to use
- Inside your schematics, add a hierachical sheet linked to the .kicad_sch of the part you need
- Add all the hierarchical pins and connect it as you wish
- Inside you PCB editor, Click on "File -> Append Board", then select the kicad_pcb from the same directory as the kicad_sch
- After all prewired parts have been appended, Click on "Update PCB from Schematics" without forgetting to check the Option "Re-link footprints to schematics symbols based on their reference designators"

### WARNING
- You cannot use the same designators as I use in my parts (For that I'll only use designators starting from 100)
More precisly each part while have a use the following designator syntax: [Standard letter][Id of the part][Part number from 00 to 99]
By "Standard Letter" I mean C for capacitors, R for resistors, etc
I will keep a list of each part Id at the bottom of this read me

# Part Ids
- 1: Power_3V3_LDO_Island
