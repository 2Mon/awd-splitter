# awd-splitter
105c rated AWD splitter pcb for 3d printers


I needed a simpler way to wire up AWD printers, so I decided to make a simple AWD splitter PCB. instead of running 12 sets of wires, 4 for motors and 8 for fans and thermistors, this means you only need to run two big 16 channel wires down to your electronics bay. On the other end of the big wires, you can just use another one of these PCBs to break it back out and connect it to your mainboard, or just crimp individual connectors on the other end. This supports four motors for AWD, as well as a thermistor and cooling fan for each. It is rated to 105c chamber temps (limited by the connectors) but could likely go higher if needed. 

To use this project, solder the connectors onto the top side of the board. Crimp your motor wires and plug them into the motor ports. Take a 16 pin connector and wire it down to your electronics bay. Do the same for the thermistors and fans if desired. 

<img width="174" height="403" alt="Screenshot 2026-02-19 at 7 44 39 PM" src="https://github.com/user-attachments/assets/5cb024f6-02f2-4da3-bab8-f663cd6c99c8" />

The PCB itself is very simple, but I tried to keep it fairly compact so it can fit easily anywhere on a printer. It uses Molex Nanofit connectors for high temp resistance and ease of crimping. 

<img width="495" height="507" alt="Screenshot 2026-02-19 at 7 45 32 PM" src="https://github.com/user-attachments/assets/32612db9-26ee-46a9-937f-804eea03a147" />

^^ wiring info also printed on PCB!

| Item                  | Price ($) | Quantity | Total ($) | Link |
|-----------------------|-----------|----------|-----------|------|
| Nanofit 2x8           | 4.60      | 4        | 18.40     | https://www.digikey.com/en/products/detail/molex/1053101216/6164149? |
| Nanofit 1x4           | 1.11      | 8        | 8.88      | https://www.digikey.com/en/products/detail/molex/1053091204/6131609? |
| Nanofit 1x2           | 0.95      | 16       | 15.20     | https://www.digikey.com/en/products/detail/molex/1053091202/6131607? |
| Nanofit 2x8 connector | 0.98      | 4        | 3.92      | https://www.digikey.com/en/products/detail/molex/1053081216/6164114? |
| Nanofit 1x4 connector | 0.41      | 8        | 3.28      | https://www.digikey.com/en/products/detail/molex/1053071204/6131602? |
| Nanofit 1x2 connector | 0.35      | 16       | 5.60      | https://www.digikey.com/en/products/detail/molex/1053071202/6131600? |
| Crimp                 | 0.34      | 100      | 34.00     | https://www.digikey.com/en/products/detail/molex/1053001300/6164097? |
| PCB                   | 3.00      | 1        | 3.00      | JLCPCB |

