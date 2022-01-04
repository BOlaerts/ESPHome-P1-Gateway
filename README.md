# ESPHome P1 Gateway
## Introduction
Simplified dummy proof design (without SMD components) based on the designs of Willem Aandewiel and Marcel Zuidwijk.
## Hardware
EasyEDA project files can be imported from the EasyEDA folder.

In the JLCPCB folder you can find the BOM and GERBER files to order all the components for the design as-is.
### Schematic
![Schematic](/../main/Pictures/Schematic.png)
### PCB
<img src="/../main/Pictures/pcb1.jpg" width="40%" height="40%"> <img src="/../main/Pictures/pcb2.jpg" width="40%" height="40%">

## Software
### Home Assistant integration
For integration in Home Assistant, I prefer using ESPHome with the DSMR component.

An example of my configuration can be found in the ESPHome folder.

More details can be found on https://esphome.io/components/sensor/dsmr.html.
### Stand alone configuration
For a stand alone configuration, I prefer the software of Willem Aandewiel

More details can be found on https://github.com/mrWheel/DSMRloggerAPI.
