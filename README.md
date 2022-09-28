# Dice-Oscillator
A simple pcb design for a 40106 square wave oscillator drone.

![image](https://user-images.githubusercontent.com/73641501/192803985-06b72328-0a4e-43cb-876a-7683e853f439.png)

NOTE: This Readme is still a work in progress

Control 6 oscillators using 6 potentiometers. 
![image](https://user-images.githubusercontent.com/73641501/192804118-fcae134e-505e-4b22-92c5-c23197dc861b.png)

Additional pins have been exposed to allow for potential vactrol implementations, or maybe you have a potentiometer that doesnt fit the footprint. 
Use cables to solder to these points.
![image](https://user-images.githubusercontent.com/73641501/192804196-ffbdac65-4d8c-4681-851c-b2f499ca48d5.png)

Can be powered by 5-12V, using 5V will output roughly ~4Vpp, while 12V will output a 10Vpp.
Power supply must be center positive, I have blown up several CD40106BE by accident by using center negative by accident.

BOM:
-  1 x CD40106BE IC
![image](https://user-images.githubusercontent.com/73641501/192804346-d96a21a2-c40e-4ea9-a860-ef5e4c8d1e94.png)

-  1 x 2.1mm Power jack OR 1 x 16 pin eurorackstyle header. USE ONLY ONE OPTION WHEN POWERING.
![image](https://user-images.githubusercontent.com/73641501/192804436-98f8455f-b5ed-4ab0-bdd1-c2d266d4c186.png)

-  7 x 10K Ohm Resistors
-  1 x 8.2K Ohm Resistor
-  6 x 10K Potentiometers
-  6 x 4.7uF Capacitors (can be altered for different audio)
-  6 x 2 pin jumpers. OR 6 toggle switches whch can be wired in place of the jumpers.
![image](https://user-images.githubusercontent.com/73641501/192804627-9d99886f-799f-4ddb-9f63-97e8c2ec08ac.png)
-  1 x LED
-  1 x 510Ohm Resistor
-  1 x 3.5mm mono jack (WQP-PJ301M-12_JACK from Thonkiconn)
