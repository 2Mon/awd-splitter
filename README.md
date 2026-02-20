# awd-splitter
105c rated AWD splitter pcb for 3d printers


I needed a simpler way to wire up AWD printers, so I decided to make a simple AWD splitter PCB. instead of running 12 sets of wires, 4 for motors and 8 for fans and thermistors, this means you only need to run two big 16 channel wires down to your electronics bay. On the other end of the big wires, you can just use another one of these PCBs to break it back out and connect it to your mainboard, or just crimp individual connectors on the other end. This supports four motors for AWD, as well as a thermistor and cooling fan for each. It is rated to 105c chamber temps (limited by the connectors) but could likely go higher if needed. 

To use this project, solder the connectors onto the top side of the board. Crimp your motor wires and plug them into the motor ports. Take a 16 pin connector and wire it down to your electronics bay. Do the same for the thermistors and fans if desired. 

<img width="174" height="403" alt="Screenshot 2026-02-19 at 7 44 39 PM" src="https://github.com/user-attachments/assets/5cb024f6-02f2-4da3-bab8-f663cd6c99c8" />

The PCB itself is very simple, but I tried to keep it fairly compact so it can fit easily anywhere on a printer. It uses Molex Nanofit connectors for high temp resistance and ease of crimping. 

<img width="495" height="507" alt="Screenshot 2026-02-19 at 7 45 32 PM" src="https://github.com/user-attachments/assets/32612db9-26ee-46a9-937f-804eea03a147" />

^^ wiring info also printed on PCB!

