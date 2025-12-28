# muon
Minimal USB-C to JST-SH daughterboard PCBs

**Currently in development; not finalized or tested.**

## Variants

### Variant A (latest revision A2)
Narrow and wide variant
![Rear](/Documentation/muon-a2-rear.png)
![Front](/Documentation/muon-a2-front.png)

### Variant B (latest revision B1)
Symmmetrical and rectangular variant
![Rear](/Documentation/muon-b1-rear.png)
![Front](/Documentation/muon-b1-front.png)

## Features

- Physically compact
  - 31.50 x 10.00 mm for Variant A
  - 20.00 x 13.00 mm for Variant B
  - Balanced minimizing of dimensions with a focus on ease of implementation on the case-side
- Physically robust
  - 2x M2.5 screws for a balance between robustness, ease of manufacturing, user-friendliness, and physical compactness
  - 1.6mm PCB to counter cable torque and resist over-tensioned screw-in by users
- Minimal, practical implementation
  - Single-sided for easy assembly - whether at a factory or reflowing at home
  - Two-layer for affordable manufacturing
  - 3D printable solder paste stencil file included (0.2mm nozzle and line width, 0.08mm layer height)
  - Asymmetrical design with protruding USB port prevents accidental reverse installation by users
- Optimized for ease of case design
  - Straightforward, rational dimensions
  - Large USB connector overhang for case-side flexibility and robustness
  - Can be mounted component-side-up or component-side-down for prioritizing ease of servicing or physical compactness respectively  
  - 3D models and example case-side implementation provided
  - Designed with aesthetics in mind to avoid detracting from case visuals  
- Proven circuitry and implementation based on the [Unified Daughterboard series](https://unified-daughterboard.github.io/#/)
  - ESD/overcurrent/overvoltage protection, single-path grounding of case via mounting screws
  - JST-SH connector with identical pinout to the Unified Daughterboard

## Dimensions
Mounting screws are M2.5.  
Only use flat screws - countersunk screws apply focused angled pressure on the screw holes and risk shattering the board apart.  
  
Recommended max diameter for screw heads/standoffs/mounting points contacting the board is 5.00mm centered on the mounting holes.  
Absolute max diameter is 6.0mm; ESD handling capabilities may be reduced when exceeding 5.00mm.  

### Variant A
Ends are roughly 5mm radius (slightly inset from a perfect arc for visual reasons).
![Dimensions](/Documentation/muon-a2-dimensions.png)

### Variant B
Corners are roughly 1.8125mm radius (slightly inset from a perfect arc for visual reasons).
![Dimensions](/Documentation/muon-b1-dimensions.png)

## Pinout

Pinout is identical to the Unified Daughterboard series.  
Only use a one-to-one cable (the same type used on the Unified Daughterboard JST-type boards; pin 1 of one end maps to pin 1 of the other end).  

![Pinout](/Documentation/muon-a2-pinout.png)
