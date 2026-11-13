# awd-splitter
A compact breakout PCB for wiring AWD 3D printers, rated for 105 °C chambers.

<img height="200" alt="Splitter PCB" src="https://cdn.hackclub.com/01a1d553-1cb0-7d79-b6e8-28dc5cdbac97/screenshot_2026-11-13_at_9.32.30___am.png" />

## Why?

AWD 3D Printers typically need 12 separate cable runs from the gantry to the electronics bay: four for motors and eight for fans and thermistors. This board collapses that into two 16 pin cables. At the electronics end, either use another PCB to break the 16 pin cables back out, or crimp on your own connectors. 

## Features

- 4 Motor Outputs (AWD)
- 4 Thermistor Outputs
- 4 Fan Outputs 
- 105 °C Temp Rating
- Molex Nano-fit connectors (easy crimping + high temp resistance)
- Small footprint

## Usage

1. Solder Molex Nano-fit connectors onto top side of PCB
2. Crimp motor wires to 4-pin connectors
3. Crimp Thermistor and Fan wires to 2-pin connectors
4. Crimp enough wire to 16 pin connectors to reach electronics bay
5. In electronics bay, plug into another splitter or crimp JST-PH connectors. 

## Pinout

Each board has two 2×8 Nano-Fit headers: one carries all four motors, the other carries all four thermistors and fans. Pins 1–8 are one row and pins 9–16 are the other. Pin numbers follow the Molex housing cavity numbers.

### 16-pin cables
 
| Pin | Motor cable | Pin | Motor cable |
| --- | --- | --- | --- |
| 1 | M1 A+ | 9 | M3 A+ |
| 2 | M1 A− | 10 | M3 A− |
| 3 | M1 B+ | 11 | M3 B+ |
| 4 | M1 B− | 12 | M3 B− |
| 5 | M2 A+ | 13 | M4 A+ |
| 6 | M2 A− | 14 | M4 A− |
| 7 | M2 B+ | 15 | M4 B+ |
| 8 | M2 B− | 16 | M4 B− |
 
| Pin | Thermistor / fan cable | Pin | Thermistor / fan cable |
| --- | --- | --- | --- |
| 1 | Thermistor 1 | 9 | Thermistor 3 |
| 2 | Thermistor 1 | 10 | Thermistor 3 |
| 3 | Fan 1 + | 11 | Fan 3 + |
| 4 | Fan 1 − | 12 | Fan 3 − |
| 5 | Thermistor 2 | 13 | Thermistor 4 |
| 6 | Thermistor 2 | 14 | Thermistor 4 |
| 7 | Fan 2 + | 15 | Fan 4 + |
| 8 | Fan 2 − | 16 | Fan 4 − |
 
Thermistors have no polarity.

### Breakout connectors
 
The pin order on the individual connectors is **not the same on every port**. Crimp each cable for the port it goes into.
 
| Port | Pin 1 | Pin 2 | Pin 3 | Pin 4 |
| --- | --- | --- | --- | --- |
| Motor 1 | B− | B+ | A− | A+ |
| Motor 2 | B− | B+ | A− | A+ |
| Motor 3 | A+ | A− | B+ | B− |
| Motor 4 | A+ | A− | B+ | B− |
| Fan 1 | − | + | | |
| Fan 2 | − | + | | |
| Fan 3 | + | − | | |
| Fan 4 | + | − | | |

## Bill of materials
 
Quantities are for **one pair** of boards (one at the motors, one at the electronics bay). Full list in [`AWD_BOM.csv`](AWD_BOM.csv).
 
| Part | Molex P/N | Unit ($) | Qty | Total ($) |
| --- | --- | --- | --- | --- |
| Nano-Fit 2×8 header | [105310-1216](https://www.digikey.com/en/products/detail/molex/1053101216/6164149) | 4.60 | 4 | 18.40 |
| Nano-Fit 1×4 header | [105309-1204](https://www.digikey.com/en/products/detail/molex/1053091204/6131609) | 1.11 | 8 | 8.88 |
| Nano-Fit 1×2 header | [105309-1202](https://www.digikey.com/en/products/detail/molex/1053091202/6131607) | 0.95 | 16 | 15.20 |
| Nano-Fit 2×8 housing | [105308-1216](https://www.digikey.com/en/products/detail/molex/1053081216/6164114) | 0.98 | 4 | 3.92 |
| Nano-Fit 1×4 housing | [105307-1204](https://www.digikey.com/en/products/detail/molex/1053071204/6131602) | 0.41 | 8 | 3.28 |
| Nano-Fit 1×2 housing | [105307-1202](https://www.digikey.com/en/products/detail/molex/1053071202/6131600) | 0.35 | 16 | 5.60 |
| Crimp terminal | [105300-2100](https://www.digikey.com/en/products/detail/molex/1053002100/7693143) | 0.11 | 140 | 15.40 |
| PCB | JLCPCB | 3.60 | 1 | 3.60 |
| **Total** | | | | **$74.28** |
