# POTATO STICK

**A Modular 3D Printed Arcade/Fight Stick Platform**

Version 0.1

<img src="/Images/Image_CAD_0.png" width="400"> 

## Purpose
This project aims to develop a modular and open-source platform for building your own fight stick or arcade controller using 3D printing, standard arcade components, and common 3D printing assembly methods and materials.

> [!IMPORTANT]
>The current v0.1 design is based on Sanwa arcade components, in particular the Sanwa JLF/JLX stick and Sanwa OBSF (snap in) push buttons. The only button layout is the vewlix 8 button layout[^1].\
>As the project develops, more options will be made available for other component form factors and button layouts.

## Design
This design leverages common techniques for creating functional 3D-printed parts, most notably, the use of heat-set inserts and geometries optimized to print without supports.

The platform is composed of three main components: the **chassis**, the **top plates**, and the **bottom plate/panels**.

The chassis is divided into two main sections: one for the joystick and one for the buttons. The button section also houses the electronics and wiring. The top plates are separate from the chassis, allowing for easy swapping between various layouts. Future revisions will include support for precision-cut steel plates and full acrylic cover for printed art.

Splitting the chassis enables the fight stick to be printed on modestly sized 3D printers while still accommodating a full 350mm (~14 inch) layout. This split also forms a structural spine through the center, providing extra support for the top plates.

<img src="/Images/Image_CAD_1.png" width="400">

The joystick is mounted to a 5mm-thick internal plate that bridges across the "stick chassis" and is secured with 6 screws. This design creates a rigid mounting point for the joystick, minimizing flex during gameplay. It also introduces another layer of modularity. This mounting plate can be swapped out to accommodate different joystick models, positions, or mounting angles.

## Requirements
- 3D Printer with a build plate of at least 220mm square
- Heat-Set insert tool (soldering iron)
- Basic metric hand tools (allen wrench set, socket/box end set)
- General fabrication, wiring, and troubleshooting skills

## Bill of Materials (BOM)
### Printed parts
| Item | Quantity | Notes |
| ---- | ---- | ---- |
| M5x25 BHCS | 5 | Connect chassis halves together |
| M5 Nut | 5 | Connect chassis halves together |
| M5 Washer | 10 | (Optional) Connect chassis halves together |
| M4x8 FHCS | 6 | Arcade stick mount to chassis |
| M4x12 FHCS | 4 | Arcade stick to mount |
| M4 Nut | 4 | Arcade stick to mount |
| M4 BHCS | 16 | Top and Bottom plate/covers |
| M3x8 BHCS | 4 | Controller board |
| M4x4 Heat-Set Insert | 22 | |
| M3x5x4 (Voron) Heat-Set Insert | 6 | Controller board and Neutrik style USB pass through connector[^2] |

### Electrical
| Item | Quantity | Notes |
| ---- | ---- | ---- |
| Sanwa JLF/JLX Stick | 1 | Various models and compatible aftermarket options |
| Sanwa OBSF-30 Button | 8 | Primary 30mm buttons for Vewlix layout |
| Sanwa OBSF-24 Button | 5 | Auxilary 24mm buttons |
| Neutrik USB Type B Pass-thru | 1 | |
| Controller Board | 1 | GP2040-CE with 88x37mm(Brooks style) mount spacing recommended |
| Wiring | Varies | |

> [!NOTE]
> BHCS - Button Head Cap Screw\
> FHCS - Flat Head Cap Screw\
> It is recommended to use hex head hardware

## Printing and Assembly

Under Construction

[^1]: Because of the tight spacing with the Vewlix layout, Sanwa OBSN (screw in) push buttons may not work.
[^2]: M3 screws should be provided with the pass through connector. If not, any M3 flat head screws of sufficient length should work.
