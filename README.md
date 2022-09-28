# Dice-Oscillator
A simple pcb design for a 40106 square wave oscillator drone.

NOTE: This Readme is still a work in progress

Control 6 oscillators using 6 potentiometers. 
Additional pins have been exposed to allow for potential vactrol implementations, or maybe you have a potentiometer that doesnt fit the footprint. 
Use cables to solder to these points.

Can be powered by 5-12V, using 5V will output roughly ~4Vpp, while 12V will output a 10Vpp.
Power supply must be center positive, I have blown up several CD40106BE by accident by using center negative by accident.

BOM:
-  1 x CD40106BE IC
-  1 x 2.1mm Power jack OR 1 x 16 pin eurorackstyle header. USE ONLY ONE OPTION WHEN POWERING.
-  7 x 10K Ohm Resistors
-  1 x 8.2K Ohm Resistor
-  6 x 10K Potentiometers
-  6 x 4.7uF Capacitors (can be altered for different audio)
-  6 x 2 pin jumpers. OR 6 toggle switches whch can be wired in place of the jumpers.

-  1 x LED
-  1 x 510Ohm Resistor
-  1 x 3.5mm mono jack (WQP-PJ301M-12_JACK from Thonkiconn)
