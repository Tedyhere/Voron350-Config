# Voron350-Config
Config for Voron350 Kit offered by CTRL-Pew

This Kit comes with the PCB Toolboard for the Extruder so be sure to print the Motor Plate for PCB board.
Also print these Parts including the files in the Clockwork folder.
https://github.com/VoronDesign/Voron-Hardware/tree/master/Afterburner_Toolhead_PCB/STLs/Clockwork

For the z Endstop I used the PCB Board Version and drilled 1.5mm holes to match the PCB board for the z endstop in the bottom.

Be sure to check the Parts Cooling and Hotend Fan wire connectors, mine were wire up reverse to what the toolboard required, this is easy to fix, I used a sim card tray tool to push down on the tiny tabs on the connectors and pulled the wires out and swapped them.

You will need to rewire your motors to EXACTLY MATCH the colors on the wiring sheet. I had to extend the B motor on the left side with the Black wire included.  I went ahead and redid both motors to give more length.. I used 4 pin Black connectors included.. Be sure to do 1 wire and connector at a time to ensure you don't cross up wires.  Doing this will make it easier in case a Motor goes bad.

For the Bed you will need to tap the two holes for the Ground and the Thermal fuse.  Follow the directions for the wiring, it seems confusing but..

My heating pad looked like this..

Wires with the wires exiting down.

Left Red wire goes to the Neutral on the Power Supply, the Black is the Thermistor wires, Middle Red I bundled up under the bed and zip tied, Right Red got a Thermal Fuse wired into it and than went to SSR

              R   B   R   R
              |   |   |   |
              |   |   |   |
              |   |   X    \
              |   |         \
              |   |           F
              |   |         /
              |   |       /
              |   |       |
              |   |       |
             PSU Board    SSR
             
