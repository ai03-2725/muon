# muon
Minimal USB-C to JST-SH daughterboard PCB

![Back](/Documentation/muon-back.png)
![Front](/Documentation/muon-front.png)

## Features

- Physically compact
  - 33.50 x 10.00 mm
  - Balanced minimizing of dimensions with a focus on ease of implementation on the case-side
- Physically robust
  - 2x M3 screws for durability and minimized risk of case machining failure
  - 1.6mm PCB to counter cable torque and resist over-tensioned screw-in by users
- Minimal, practical implementation
  - Single-sided for easy assembly - whether at a factory or reflowing at home
  - Two-layer for affordable manufacturing
  - 3D printable solder paste stencil file included (0.2mm nozzle and line width, 0.08mm layer height)
  - 3D models and example case-side implementation provided
  - Asymmetrical design with protruding USB port prevents accidental reverse installation
- Proven circuitry and implementation based on the [Unified Daughterboard series](https://unified-daughterboard.github.io/#/)
  - ESD/overcurrent/overvoltage protection, single-path grounding of case via mounting screws
  - JST-SH connector with identical pinout to the Unified Daughterboard

## Pinout

Pinout is identical to the Unified Daughterboard series.  
Only use a one-to-one cable (the same type used on the Unified Daughterboard JST-type boards; pin 1 of one end maps to pin 1 of the other end).  

![Pinout](/Documentation/pinout.png)

## Dimensions

![Dimensions](/Documentation/dimensions.png)
