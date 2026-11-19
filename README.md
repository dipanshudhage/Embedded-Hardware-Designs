# Embedded-Hardware-Designs

A collection of KiCad schematics, PCB layouts, and hardware design files covering microcontroller boards, power/switching modules, USB-serial interfaces, LED controllers, and analog circuits.

## Repository Contents

| Folder | Description | Key Files Included |
| :--- | :--- | :--- |
| `ARDUINO MCU BOARD` | Microcontroller board design[cite: 3] | `.kicad_sch`, `.kicad_pcb`, `.kicad_pro`, `.kicad_prl`[cite: 3] |
| `ARDUINO PRO MINI` | Compact Arduino Pro Mini hardware layout[cite: 3] | `.kicad_sch`, `.kicad_pcb`, `.kicad_pro`, `.kicad_prl`, `.csv`[cite: 3] |
| `LED` | Basic LED circuit design[cite: 3] | `.kicad_sch`, `.kicad_pcb`, `.kicad_pro`, `.kicad_prl`, `fp-lib-table`[cite: 3] |
| `LED FLASHING CIRCUIT` | Flashing LED circuit schematic and layout[cite: 3] | `.kicad_sch`, `.kicad_pcb`, `.kicad_pro`, `.kicad_prl`[cite: 3] |
| `LED sequential flasher` | Sequential LED flasher circuit[cite: 3] | `.kicad_sch`, `.kicad_pcb`, `.kicad_pro`, `.kicad_prl`[cite: 3] |
| `Light-Activated LED Controller` | Light-triggered LED control circuit[cite: 3] | `.kicad_sch`, `.kicad_pcb`, `.kicad_pro`, `.kicad_prl`[cite: 3] |
| `Qwiic_Power_Switch` | Power switching hardware module[cite: 3] | `.kicad_sch`, `.kicad_pcb`, `.kicad_pro`, `.kicad_prl`[cite: 3] |
| `SMART NODE – ESP32 ROOM CONTROLLER` | ESP32-based room controller hardware design[cite: 3] | `.kicad_sch`, `.kicad_pcb`, `.kicad_pro`, `.kicad_prl`[cite: 3] |
| `Serial-Basic-CH340C-and-USBC` | USB-C to UART serial interface using CH340C[cite: 3] | `.kicad_sch`, `.kicad_pcb`, `.kicad_pro`, `.kicad_prl`, `.step`[cite: 3] |
| `TSH82 Configurable Op-Amp Board` | Configurable operational amplifier board using TSH82[cite: 3] | `.kicad_sch`, `.kicad_pcb`, `.kicad_pro`, `.kicad_prl`[cite: 3] |

## Tools & Workflow
* **EDA Suite:** KiCad (`.kicad_pro`, `.kicad_sch`, `.kicad_pcb`)[cite: 3]
* **3D & Manufacturing Data:** STEP 3D model (`Serial-Basic-CH340C-and-USBC.step`) and CSV data (`ARDUINO PRO MINI.csv`)[cite: 3]

## How to Use
1. Clone or download the repository to your local machine.
2. Open any project folder and launch the `.kicad_pro` file in **KiCad** to inspect schematics, footprints, and PCB layouts[cite: 3].
3. Run Design Rule Checks (DRC) and Electrical Rule Checks (ERC) and verify component values/footprints before ordering PCBs or assembling hardware.

## Hardware & Safety Disclaimer
These schematic, PCB, and hardware files are shared for educational, learning, and prototyping purposes. Always review schematics, power ratings, isolation clearances, and component datasheets carefully before powering up or manufacturing any circuit.

## License
This repository is licensed under the **MIT License** — see the [`LICENSE`](LICENSE) file for details[cite: 3].

## Author
**Dipanshu Dhage**
