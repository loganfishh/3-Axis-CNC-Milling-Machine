# 3-Axis-CNC-Milling-Machine
A repository showcasing the design and construction of my 3-axis CNC milling machine featuring drawings/designs, circuit diagrams, and software used. I began and finished this project over the course of the summer of 2024 in a span of approximately two and a half months.

# 1. CAD Model & Final Assembly
## 1.1 CAD Model
![Render of the CAD model](https://github.com/loganfishh/3-Axis-CNC-Milling-Machine/blob/main/images/cad_cnc_router_iso_wm.png)
## 1.2 Final Assembly
![Image of the final assembly](https://github.com/loganfishh/3-Axis-CNC-Milling-Machine/blob/main/images/cnc_full_setup.jpg)

# 2. Example Drawing & Circuit Diagram
## 2.1 Example Drawing of Right Side Gantry Support
Drawings like the one below were created for all non-standard components which includes the entire gantry assembly as well as any adapters between standard parts.
![Technical drawing of the right side gantry support](https://github.com/loganfishh/3-Axis-CNC-Milling-Machine/blob/main/images/right_side_gantry_support.png)
## 2.2 Circuit Diagram
Not currently available, but may upload one if someone requests it. See [section 2.3](#23-wiring) below for an image of the actual wiring.
## 2.3 Wiring
![Annotated image of the wiring inside the electronics enclosure](https://github.com/loganfishh/3-Axis-CNC-Milling-Machine/blob/main/images/wiring_annotated.png)

# 3. Bill of Materials
The numerous standard parts will not be explicitly provided. The non-standard parts were mostly made from 1/4" and 3/8" thick aluminum plates, observed at the locations mentioned in [section 2.1](#21-example-drawing-of-right-side-gantry-support). The spoilboard was cut to shape from 3/8" MDF board, and the electronics enclosure was made from 1/2" thick Sande plywood. The frame was made from 3030 T slot aluminum extrusion.

# 4. Tools & Software
## 4.1 Tools Used in Manufacturing
- Drill press
  - HSS bits used with WD-40 as a cutting fluid for aluminum
- Portable table saw
  - Fine-tooth carbide-tipped blade used with WD-40 as a cutting fluid for aluminum
- Belt sander
- Bench grinder
- Tap and die set
- Various handheld tools
  - Cordless drill/driver
  - Angle grinder
  - Screwdrivers
  - Allen wrenches
  - Clamps
## 4.2 Software Used in Manufacturing
- Autodesk Fusion
  - For all CAD models/drawings
- Google Sheets
  - For budget tracking
## 4.3 Software Used in CNC Mill
- Autodesk Fusion
  - For CAM and generating toolpaths
- Universal G-Code Sender (Laptop)
  - For outputting G-code to Arduino Uno
- GRBL (Arduino Uno)
  - For interpreting G-code to stepper and spindle movement

# 5. Various Specifications
Here are some common metrics used to measure CNC machines for my final assembly:
- Cutting area: approximately 14"x7.5"x4"
  - 105 in<sup>2</sup>, 420 in<sup>3</sup>
- Max feedrate: 2,540 mm/min or 100 ipm
- Max acceleration: 254 mm/s<sup>2</sup> or 10 in/s<sup>2</sup>
- Resolution: 2 &mu;m at 1/16 microstep (theoretically)
- Spindle speed: 0-12000 rpm
- Capable of plastic, wood, or aluminum milling
  - Have not tested with stronger material(s)

# 6. Project Showcase
## 6.1 Dragon Relief
[Credit to @stlfilesfree on cults3d.com for the 3D model!](https://cults3d.com/:19242)
![Image of a relief of a dragon made with my CNC mill](https://github.com/loganfishh/3-Axis-CNC-Milling-Machine/blob/main/images/dragon_relief.jpg)
## More Coming Later...
