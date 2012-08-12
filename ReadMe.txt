You need 3 major parts.
1: Slic3r
2: Printrun
3: Marlin

1: Slic3r – http://slic3r.org/
Slic3r is a perl program that slices your model and turns it into Gcode for printing.
The most recent version is http://slic3r.org/2012/08/21-slic3r-091-is-out/
There are pre-compiled binaries for Mac, Windows, and Linux; for 32 or 64 bit processors. 
You need the slic3r config file (NextFabMendelMax.ini) included here that has been optimized for your printer somewhat.

2: Printrun – https://github.com/kliment/printrun
Printrun allows you to control your printer, move axes, and print the Gcode generated for you by Slic3r. It's written in Python, but uses wx-python to make the GUI.
There are precompiled binaries for Mac and Windows here: http://koti.kapsi.fi/~kliment/printrun/
Linux users can install the dependencies and pull the source from Github

3: Marlin – https://github.com/ErikZalm/Marlin
The Marlin firmware runs on the RAMPS stack and interprets Gcode from your computer into movement and extrusion. It needs to be configured for each printer, so use the firmware included here and program it with the Arduino IDE.
You can get the Arduino IDE from here: http://arduino.cc/en/Main/Software