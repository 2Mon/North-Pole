# North Pole
 
### Compact Cantilever Polar 3D Printer
 
<img width="400" alt="North Pole" src="https://github.com/user-attachments/assets/20b6b7a1-4984-4bed-9f7b-9d0c09feb255" />

## About
North Pole is a cantilever polar 3d printer with a spinning 120mm bed. Instead of moving the bed in X and Y, the bed rotates (theta) while the toolhead moves along a single cantilevered arm (rho). 

The frame is a compact 230×180mm rectangle of MISUMI 2040 and 4040 extrusion, topped with an aluminum plate that adds rigidity and gives the bed and motors a solid mount. The toolhead is kept as light as possible, with a TZ V6 hotend and a bowden HGX Lite. The bed is made with a piece of aluminum sheet metal topped with Kapton tape to avoid needing a heater or slip ring. 

I designed this for [Hack Club](https://hackclub.com) Highway.

HUGE Thank you to PCBWAY for sponsoring the aluminum sheet metal for this project! It wouldn't have been possible without them! The parts are super high quality and were delivered right on time for me to be able to work on my build. 

[CAD on Onshape](https://cad.onshape.com/documents/8edeb01ab6b0e2192901165c/w/d814f36a7d6152b32be36afc/e/db78d6bfa419989c16b0d558)

## Bed
 
<img width="350" alt="North Pole bed system" src="https://github.com/user-attachments/assets/b4b2bc31-e98d-48e6-8942-788333c7c4ff" />

The bed spins on a 6812 bearing clamped between two printed parts and bolted through the aluminum plate. The motor sits on a slider so the belt loop can be tensioned.

# Rho Axis
 
<img width="400" alt="Rho motor mount" src="https://github.com/user-attachments/assets/37050fae-0857-42c0-89b1-d6693dbc425c" />

The rho arm is an MGN9H rail mounted to the Z carriage. The motor mount is a solid printed block sandwiched together with long M3 bolts, and the idler at the far end is kept small to keep weight off the end of the cantilever. The Z axis is a 150mm leadscrew stepper driving an MGN12H carriage.

## Toolhead
 
<img width="300" alt="North Pole toolhead" src="https://github.com/user-attachments/assets/09b6044a-1959-4a07-8153-d99379a440d6" />

The toolhead is a single print, with a 2510 fan for hotend cooling and a 4010 blower for part cooling. The HGX Lite rides on the Z carriage instead of the toolhead, which keeps the toolhead light while keeping the bowden tube short.

## Wiring
 
<img width="600" alt="Wiring diagram" src="https://github.com/user-attachments/assets/b8f81c3a-ad2e-4415-bb95-c2a103417c6d" />

The SKR Pico lives in the electronics bay. The PSU and Pi are mounted externally to keep the frame compact.

## BOM
 
| Item | Price | Qty | Total | Link |
| :--- | ---: | :---: | ---: | :---: |
| NEMA 17 (3 pack) | $30.45 | 1 | $30.45 | [↗](https://www.aliexpress.us/item/2251832386575349.html) |
| GT2 Belt | $7.72 | 1 | $7.72 | [↗](https://www.aliexpress.us/item/2251832667244886.html) |
| 20T Pulley (2 pack) | $4.99 | 1 | $4.99 | [↗](https://www.aliexpress.us/item/2251832808788159.html) |
| 20T Idler | $3.99 | 1 | $3.99 | [↗](https://www.aliexpress.us/item/2251832539995194.html) |
| 80T Pulley | $7.65 | 1 | $7.65 | [↗](https://www.aliexpress.us/item/3256805291833644.html) |
| 280mm Belt Loop | $0.55 | 2 | $1.10 | [↗](https://www.aliexpress.us/item/2255800049977727.html) |
| MGN12H 150mm Rail | $17.11 | 1 | $17.11 | [↗](https://www.aliexpress.us/item/2251832643511407.html) |
| MGN9H 150mm Rail | $16.65 | 1 | $16.65 | [↗](https://www.aliexpress.us/item/2251832586981749.html) |
| 2510 Fan | $7.62 | 1 | $7.62 | [↗](https://www.aliexpress.us/item/3256808076821944.html) |
| 4010 Blower Fan | $13.84 | 1 | $13.84 | [↗](https://www.aliexpress.us/item/3256801655319095.html) |
| V0 Leadscrew Motor | $24.80 | 1 | $24.80 | [↗](https://www.aliexpress.us/item/3256805672589159.html) |
| 6812 Bearing | $9.58 | 1 | $9.58 | [↗](https://www.aliexpress.us/item/3256807233759178.html) |
| HGX Lite Extruder | $20.54 | 1 | $20.54 | [↗](https://www.aliexpress.us/item/3256806387907092.html) |
| Kapton Tape | $9.34 | 1 | $9.34 | [↗](https://www.aliexpress.us/item/3256805157658322.html) |
| TZ V6 Hotend | $20.58 | 1 | $20.58 | [↗](https://www.aliexpress.us/item/3256808497218562.html) |
| SKR Pico | $30.99 | 1 | $30.99 | [↗](https://www.aliexpress.us/item/3256808864716770.html) |
| Raspberry Pi 3B | $26.78 | 1 | $26.78 | [↗](https://www.digikey.com/en/products/detail/raspberry-pi/SC0563/6235381) |
| ECAS Collet (3 pack) | $5.26 | 1 | $5.26 | [↗](https://www.aliexpress.us/item/2251832747833403.html) |
| HFS5-2040-230-LWH-RCH | $16.00 | 2 | $32.00 | [↗](https://us.misumi-ec.com/vona2/detail/110302684350/?HissuCode=HFS5-2040-230-LWH-RCH) |
| HFS5-2040-160 | $5.47 | 1 | $5.47 | [↗](https://us.misumi-ec.com/vona2/detail/110302684350/?HissuCode=HFS5-2040-160) |
| HFS5-2040-205 | $5.47 | 1 | $5.47 | [↗](https://us.misumi-ec.com/vona2/detail/110302684350/?HissuCode=HFS5-2040-205) |
| HFS5-4040-160-AH66.5 | $12.19 | 1 | $12.19 | [↗](https://us.misumi-ec.com/vona2/detail/110302684530/?HissuCode=HFS5-4040-160-AH66.5) |
| M5 Self-Tapping Screws | $0.76 | 10 | $7.60 | |
| 24V PSU | $17.36 | 1 | $17.36 | [↗](https://a.aliexpress.com/_mrllXad) |
| M3/M4/M5 Screw Kit | $14.58 | 1 | $14.58 | [↗](https://www.aliexpress.us/item/3256809277967067.html) |
| Aluminum Top Plate | $30.73 | 1 | $30.73 | *PCBWay* |
| **Total** | | | **$384.39** | |
 
| **TOTAL**                |        |          | **384.39**   |                                                                                                                        |
