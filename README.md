# Breadboard Power Supply

A compact and versatile power supply designed specifically for breadboard prototyping. This PCB provides multiple regulated voltage outputs (3.3V, 5V, and 12V) from a single DC barrel jack input, making it ideal for electronics hobbyists and students.

## Features

- **Multiple Voltage Outputs**: Provides 3.3V, 5V, and 12V regulated outputs
- **DC Barrel Jack Input**: Standard barrel jack connector with internal switch for easy power connection
- **Breadboard Compatible**: Designed to fit directly onto standard breadboards
- **Compact Design**: Small form factor optimized for breadboard use
- **Regulated Power**: Ensures stable voltage outputs for sensitive electronic components

## Schematic

![PCB Schematic](pcb%20schematic.png)

The schematic shows the complete circuit design including voltage regulators and power distribution.

## PCB Layout

![PCB Layout](pcb%20layout.png)

The PCB layout displays the copper traces, component placement, and board dimensions.

## 3D View

![PCB 3D View](pcb%203d%20view.png)

A rendered 3D visualization of the assembled PCB showing component placement and board appearance.

## Specifications

- **Input Voltage**: 12V DC (via barrel jack)
- **Output Voltages**: 
  - 3.3V regulated output
  - 5V regulated output
  - 12V pass-through
- **PCB Design**: KiCad 9.0
- **Board Type**: 2-layer PCB
- **Project Version**: Version 1

## Getting Started

### Prerequisites

- KiCad 9.0 or later (for viewing/editing the design files)
- PCB manufacturing service (for fabrication)
- Required components (see BOM - Bill of Materials)

### Opening the Project

1. Install [KiCad](https://www.kicad.org/) version 9.0 or later
2. Clone this repository
3. Open the project file: `Bread power Supply.kicad_pro`
4. View the schematic: `Bread power Supply.kicad_sch`
5. View the PCB layout: `Bread power Supply.kicad_pcb`

### Manufacturing

1. Export Gerber files from KiCad
2. Send to your preferred PCB manufacturer
3. Assemble components according to the schematic
4. Test voltage outputs before connecting to sensitive electronics

## Project Files

- `Bread power Supply.kicad_pro` - KiCad project file
- `Bread power Supply.kicad_sch` - Schematic file
- `Bread power Supply.kicad_pcb` - PCB layout file
- `pcb schematic.png` - Schematic diagram image
- `pcb layout.png` - PCB layout image
- `pcb 3d view.png` - 3D rendered view

## Usage

1. Connect a 12V DC power supply to the barrel jack connector
2. The power switch on the barrel jack controls the entire board
3. Connect your breadboard circuits to the appropriate voltage outputs:
   - Use 3.3V for low-voltage ICs and sensors
   - Use 5V for standard logic circuits and microcontrollers
   - Use 12V for motors or other higher-voltage components
4. Ensure your load does not exceed the current ratings of the voltage regulators

## Safety Notes

⚠️ **Important Safety Information:**
- Always check voltage outputs with a multimeter before connecting sensitive components
- Ensure proper heat dissipation for voltage regulators under load
- Do not exceed the maximum current ratings of the voltage regulators
- Use appropriate fusing on the input for overcurrent protection

## Author

**Matthew**

## Date

December 19, 2025

## License

This project is open-source hardware. Please check with the author for specific licensing terms.

---

*Designed with KiCad 9.0*
