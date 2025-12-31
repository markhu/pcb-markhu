# pcb-markhu
PCB projects ⏚

## Small PTH Board

A demonstration KiCad project for a small PTH (Plated Through Hole) circuit board.

### Specifications

- **Board Size**: 80mm x 60mm (maximum dimensions)
- **Component Type**: PTH (Plated Through Hole) components only
- **Layer Count**: 2-layer board (Front and Back copper)
- **Board Thickness**: 1.6mm standard
- **Compatible Manufacturers**: 
  - OSHpark.com
  - PCBway.com
  - Other small-batch PCB fabrication services

### Features

- Simple LED blink circuit demonstration
- Standard PTH footprints:
  - 2-pin power connector (2.54mm pin header)
  - Through-hole resistor (330Ω)
  - 5mm LED
- Ground plane on both layers
- Proper design rules for small-batch fabrication

### Design Rules

- Minimum track width: 0.25mm (9.8 mil)
- Minimum clearance: 0.2mm (7.9 mil)
- Via size: 0.8mm diameter / 0.4mm drill
- Standard PTH pad sizes (1.6-1.8mm)

### Files Included

- `small-pth-board.kicad_pro` - KiCad project file
- `small-pth-board.kicad_sch` - Schematic file
- `small-pth-board.kicad_pcb` - PCB layout file

### Getting Started

1. Open the project in KiCad 6.0 or later
2. Review the schematic in the schematic editor
3. Open the PCB layout to see the board design
4. Generate Gerber files for manufacturing:
   - File → Fabrication Outputs → Gerbers (.gbr)
   - File → Fabrication Outputs → Drill Files (.drl)

### Manufacturing Notes

This board design follows standard specifications that are compatible with most PCB manufacturers including OSHpark and PCBway. The design uses:

- Standard 2-layer stackup
- Minimum features well within typical manufacturing capabilities
- PTH components only (no SMD components)
- Clear silkscreen markings
- Proper board outline on Edge.Cuts layer
