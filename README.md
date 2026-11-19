# Embedded-Hardware-Designs

A collection of KiCad schematics, PCB layouts, 3D renders, STEP models, and hardware design files covering microcontroller boards, power/switching modules, USB-serial interfaces, LED controllers, and analog circuits.

## Repository Contents

| Folder | Description | Documentation & Assets |
| :--- | :--- | :--- |
| `ARDUINO MCU BOARD` | Microcontroller board design | [Project README](ARDUINO%20MCU%20BOARD/README.md) · `ASSETS/` |
| `ARDUINO PRO MINI` | Compact Arduino Pro Mini hardware layout | [Project README](ARDUINO%20PRO%20MINI/README.md) · `ASSETS/` · `.csv` |
| `LED` | LED circuit schematic, PCB layout, and 3D views | [Project README](LED/README.md) · `ASSETS/` |
| `LED FLASHING CIRCUIT` | Flashing LED circuit schematic and layout | [Project README](LED%20FLASHING%20CIRCUIT/README.md) · `ASSETS/` |
| `LED sequential flasher` | Sequential LED flasher circuit design | [Project README](LED%20sequential%20flasher/README.md) · `ASSETS/` |
| `Light-Activated LED Controller` | Light-triggered LED control circuit | [Project README](Light-Activated%20LED%20Controller/README.md) · `ASSETS/` |
| `Qwiic_Power_Switch` | Power switching hardware module | [Project README](Qwiic_Power_Switch/README.md) · `Assets/` |
| `SMART NODE – ESP32 ROOM CONTROLLER` | ESP32-based room controller hardware design | [Project README](SMART%20NODE%20%E2%80%93%20ESP32%20ROOM%20CONTROLLER/README.md) · `ASSETS/` |
| `Serial-Basic-CH340C-and-USBC` | USB-C to UART serial interface using CH340C | [Project README](Serial-Basic-CH340C-and-USBC/README.md) · `Assets/` |
| `TSH82 Configurable Op-Amp Board` | Configurable operational amplifier board using TSH82 | [Project README](TSH82%20Configurable%20Op-Amp%20Board/README.md) · `Assets/` |

## Tools & Workflow
* **EDA Suite:** KiCad (`.kicad_pro`, `.kicad_sch`, `.kicad_pcb`)
* **Visuals & 3D CAD:** Schematic, layout, and front/back 3D PNG renders plus `.step` 3D models

## How to Use
1. Browse any project folder's `README.md` for a quick look at its schematic, PCB layout, and 3D front/back views.
2. Open the `.kicad_pro` file in **KiCad** to inspect schematics, footprints, and board layouts.
3. Run Electrical Rule Checks (ERC) and Design Rule Checks (DRC) and verify component ratings/footprints before fabrication or assembly.

## Hardware & Safety Disclaimer
These schematic, PCB, and hardware files are shared for educational, learning, and prototyping purposes. Always review schematics, power ratings, isolation clearances, and component datasheets carefully before powering up or manufacturing any circuit.

## License
This repository is licensed under the **MIT License** — see the [`LICENSE`](LICENSE) file for details.

## Author
**Dipanshu Dhage**
