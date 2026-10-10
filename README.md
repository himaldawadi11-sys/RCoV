# RCoV PCB

An astronomy-themed PCB designed by **SpaceYatri**, made with KiCad.

The front has a gear and the club name. The back has a pulsar map (like the one on the Pioneer and Voyager spacecraft) and a falling meteor.



### Schematic
<img width="376" height="325" alt="Screenshot 2026-10-10 195406" src="https://github.com/user-attachments/assets/c8689b02-db53-47aa-84c8-3e729148f6d9" />



### PCB Layout
<img width="350" height="410" alt="Screenshot 2026-10-10 195338" src="https://github.com/user-attachments/assets/47a0bf49-ea9b-4af1-bede-3d97b2b29b28" />



### 3D View
<img width="515" height="473" alt="Screenshot 2026-10-10 195250" src="https://github.com/user-attachments/assets/2d3edadb-1852-4ea4-8588-360d70ddaea6" />

  <img width="530" height="473" alt="Screenshot 2026-10-10 195311" src="https://github.com/user-attachments/assets/7cf44be0-7921-43f6-b4d8-75bb2807197e" />



## Files

| File | Description |
| --- | --- |
| `RCoV(PCB).kicad_pro` | KiCad project file |
| `RCoV(PCB).kicad_sch` | Schematic |
| `RCoV(PCB).kicad_pcb` | PCB layout |
| `RCoV(PCB).zip` | Gerber and drill files, ready to upload to a PCB fab |

## How to open

1. Install [KiCad](https://www.kicad.org/download/).
2. Download or clone this repository.
3. Open `RCoV(PCB).kicad_pro` in KiCad.


## Bill of Materials

- 1 x NE555P timer IC (U1), DIP-8
- 6 x 5 mm LED (D1-D6)
- 6 x 2N3904 NPN transistor (Q1-Q6), TO-92L
- 6 x 470 ohm resistor (R1-R6)
- 3 x 47 kohm resistor (R7, R8, R10)
- 1 x 4.7 kohm resistor (R11)
- 1 x photoresistor (R9)
- 1 x 10 uF electrolytic capacitor (C1)
- 1 x 6 mm push button (SW1)
- 2 x CR2032 battery holder (BT1, BT2), Keystone 3034
- 2 x CR2032 coin cell

Full list with footprints is in BOM.csv.

## About

Made with love by SpaceYatri for Robotics Club of Valmiki.
