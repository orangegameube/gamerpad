# Gamerpad
The gamerpad is a basic macropad with multiple keys, 3 LEDs, and a 01x04 connector. It was constructed by reverse-engineering Hack Club's Hackpad and Orpheuspad projects. Its case was designed using CAD software on Fusion360 and it uses QMK firmware. It was created as a introductory project to hardware and electronics.

# Features
* Custom-fitting case with holes to show electronics on the PCB
* RP2040
* 15 keys
* 3 LEDs
* QMK/VIA support

# CAD Model
The full case is made of 3 main parts: The base plate, an interior wall meant to hold the PCB in place, and the top plate covering the PCB. You can assemble it using 5 M3 bolts. 
<img width="1020" height="767" alt="image" src="https://github.com/user-attachments/assets/5f800202-ed46-4013-b343-63d9b0b1f98a" />
The model was made using Fusion360.

# Hardware
The schematic and PCB were made using KiCad.
For the LEDs, I used footprints found on the Hack Club Hackpad resources page, which were for the SK6812MINI-E. 

<img width="1057" height="737" alt="Screenshot 2026-06-26 102535" src="https://github.com/user-attachments/assets/a517877d-04de-48f9-a8be-76e7e5980197" />
Schematic
<img width="1152" height="830" alt="Screenshot 2026-06-26 102512" src="https://github.com/user-attachments/assets/4a255bfa-d572-4436-b8a1-86e5528d13d0" />
PCB

# Firmware
This project uses QMK firmware. The keys are mapped to function as calculator keys, but you can change it up in the QMK key configuration to whatever you like.

# BOM
* 1x XIAO RP2040
* 1x Case (3 3D-printed parts)
* 15x Cherry MX Switches
* 15x DSA Keycaps
* 5x M3x16mm SCHS Bolts
* 15x 1N4148 Diodes
* 3x SK6812MINI-E LEDs

# Project Reflections
It was a lot easier than I expected to get information on how keyboard hardware works from the internet, and I feel pretty confident in making schematics now (even though I had never made one before this project)! However, I still feel very lost regarding QMK, so I hope to dive deeper into it through my next project. Making the case was relatively easy, as I've used Fusion360 often in the past, but the project definitely helped me improve my current skills.
