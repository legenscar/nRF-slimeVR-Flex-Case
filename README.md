# FlexCase -  nRF SlimeVR 
FlexCase is a 3D printable case design for stacked ProMicro nrf52840 based SlimeVR trackers that can accommodate a large 250mAh battery without sacrificing comfort, utilizing Heat-set inserts for increased repairability. At only 8mm in height and with a flexible TPU bridge, you should only feel the straps!

In addition, space is provided under the ProMicro as well to allow soldering from under the ProMicro. I advise you to read through the whole README before starting. 

## What you will need
### tools:
- Soldering iron
- solder
- wire cutter / scissors
- solder flux (optional)
- heat-set insert tip for your soldering iron
- Kapton tape
- access to a 3D printer or 3D printing service
- multimeter (optional)
- pliers (optional)
### per tracker:
- 4x 5x4xM3 (length x outer diameter x inner diameter) brass heat inserts
- 4x 6mm M3 Flathead screws
- 5x 3D printed parts
- 1x 3.7V Lipo battery (smaller than 6x17x31mm) with wires longer than 60mm
- 1x ProMicro nRF52840
- 1x IMU of your choice
- 1x 2-pin button
- Wire (31.2mm)
- Hook side Velcro

## Assembly
### Soldering 
Refer to the official SlimeVR docs (https://docs.slimevr.dev/smol-slimes/hardware/smol-tracker.html) for soldering your ProMicros. Beware that for your ProMicros to fit this case, the IMU Breakout board + ProMicro together should not exceed 4mm in height. Note: Be careful not to short the components near the buttons if the button housing is made of metal. 

### Printing
For each tracker you will need 5 printed parts. The parts for the cases (4 per tracker) are to be printed with a hard material (PLA, PETG etc.) while the TPU bridge should, as the name suggests, be printed with a flexible material (TPU 95A etc.). While printing, make sure to enable supports. 

### Assembling
First, insert the heat inserts into the case, 2 on each side of one tracker.

Now its time to solder the battery to the ProMicros. Cut the red wire to 60mm and the black wire to 55mm. Pull the wires through the little opening in the TPU bridge and solder them to the ProMicro. Keep the TPU bridge away while doing so to avoid damage. 

Now you can fit everything into the case! While closing the case, make sure not to pinch any wires. Pliers will be very useful here! Screw everything together and youre done!

## Notes
- Depending on your printer and filament some sanding is required. 
- Ive designed the cases so that the ProMicro clicks in and should not move on its own, however if you want to make sure it stays you can use some double sided tape.


