# PCB Golden Arduino
The board functions like a commercial Arduino board successfully but with less noise.

## Keywords for Technologies/hardware used:
Printed Circuit Board Design, Printed Circuit Board Manufacturing, Analog Circuit Design, Soldering, Schematic, Arduino, Altium Designer, Oscilloscope

## Requirements: 
When powering the board, the indicator LEDs light up successfully stating that the PCB Design was accurate. 

The bootloader was burned successfully.

Any sketch written on the Arduino IDE was able to run on the board. 

When compared with the commercial Arduino, the switching noise when measured with the noise shield was less. 

The inrush current was within range.

## Schematic
![image](https://github.com/ishassharma/PCB--Golden-Arduino/assets/75325587/99dd34de-6a53-44b3-91a2-545f5330f1b3)

## Board 
![image](https://github.com/ishassharma/PCB--Golden-Arduino/assets/75325587/6a439f4c-427e-4883-9a45-6802cada2b1f)

## Board PCB Layout
![image](https://github.com/ishassharma/PCB--Golden-Arduino/assets/75325587/aa98bc0b-30b9-4c41-a9f5-a3a78b8eb9db)

## Conclusion
The noise from the board was comparatively less as compared to the commercial Arduino. This was done by using the minimal number of cross-under lengths, continuous return paths for signal trace, keeping the crystal, filter capacitors and decoupling capacitors close to the Ics, keeping the Data traces short, keeping Tx and Rx traces short, top-layer signal and power routing, using ferrite filter on noise-sensitive pins, low loop inductance decoupling caps, routing adjacent signal lines as far from each other as possible to reduce cross-talk and noise.

