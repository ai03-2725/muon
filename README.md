# muon
Minimal USB-C to JST-SH daughterboard PCB

**Currently in development; not finalized or tested.**

![Rear](/Documentation/muon-a2-rear.png)
![Front](/Documentation/muon-a2-front.png)

## Features

- Physically compact
  - 31.50 x 10.00 mm
  - Balanced minimizing of dimensions with a focus on ease of implementation on the case-side
- Physically robust
  - 2x M2.5 screws for a balance between robustness, ease of manufacturing, and physical compactness
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

## Dimensions
Mounting screws are M2.5.  
Only use flat screws - countersunk screws apply focused angled pressure on the screw holes and risk shattering the board apart.  
  
Recommended max diameter for screw heads/standoffs/mounting points contacting the board is 5.00mm centered on the mounting holes.  
Absolute max diameter is 6.2mm; ESD handling capabilities may be reduced when exceeding 5.00mm.  
![Dimensions](/Documentation/muon-a2-dimensions.png)

## Pinout

Pinout is identical to the Unified Daughterboard series.  
Only use a one-to-one cable (the same type used on the Unified Daughterboard JST-type boards; pin 1 of one end maps to pin 1 of the other end).  

![Pinout](/Documentation/muon-a2-pinout.png)
