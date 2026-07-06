# Flex case -  nRF SlimeVR 
Flex Case is a 3D printable case design for stacked ProMicro nrf52840 based SlimeVR trackers that can accommodate a large 250mAh battery without sacrificing comfort, utilizing Heat-set inserts for increased repairability and a flexible TPU bridge for a comfier fit! 

In addition, space is provided under the ProMicro as well to allow soldering from under the ProMicro. I advise you to read through the whole README before starting. 

## What you will need
### tools:
- Soldering iron
- solder
- wire cutter / scissors
- solder flux (optional)
- heat-set insert tip for your soldering iron
- access to a 3D printer or 3D printing service
- multimeter (optional)
### per tracker:
- 4x 5x4xM3 (length x outer diameter x inner diameter) brass heat inserts
- 4x 6mm M3 Flathead screws
- 5 3D printed parts
- 3.7V Lipo battery (smaller than 6x17x31mm) with wires longer than 60mm
- ProMicro nRF52840
- IMU of your choice
- 2 pin button
- Wire

## Assembly
### Soldering 
Refer to the official SlimeVR docs (https://docs.slimevr.dev/smol-slimes/hardware/smol-tracker.html) for soldering your ProMicros. Beware that for your ProMicros to fit this case, the IMU Breakout board + ProMicro together should not exceed 4mm in height

### Printing
For each tracker you will need 5 printed parts. The parts for the cases (4 per tracker) are to be printed with a hard material (PLA, PETG etc.) while the TPU bridge should, as the name suggests, be printed with a flexible material (TPU 95A etc.). While printing, make sure to enable supports for the case pieces. 

### Assembling
First, insert the heat inserts into the case, 2 on each side of one tracker.

Now its time to solder the battery to the ProMicros. Cut the red wire to 60mm and the black wire to 55mm. Pull the wires through the little opening in the TPU bridge and solder them to the ProMicro. Keep the TPU bridge away while doing so. 


