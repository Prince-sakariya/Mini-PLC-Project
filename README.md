# Mini-PLC-Project

Arduino-based Mini PLC with custom PCB and 3D-printed housing.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Hardware Components](#hardware-components)
- [Software Components](#software-components)
- [Installation](#installation)
- [Usage](#usage)
- [Schematics and PCB Design](#schematics-and-pcb-design)
- [3D Printed Housing](#3d-printed-housing)
- [Documentation](#documentation)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Project Overview
This project involves the creation of a **Programmable Logic Controller (PLC)** utilizing an Arduino microcontroller. The system features 8 input and 8 output channels, a custom-designed PCB, and a 3D-printed housing. This cost-effective and scalable solution is ideal for various automation tasks in educational settings.

## Features
- 8 digital input channels
- 8 digital output channels
- Custom-designed PCB for reliable connections
- 3D-printed housing for durability and ease of use
- Compatibility with Arduino Uno and Mega
- Galvanic isolation for input and output channels
- Flexible power supply options

## Hardware Components
- **Arduino Uno/Mega**
- **Optocouplers** (PC817)
- **P-channel MOSFETs**
- **DC-DC Buck-Boost Converter** (HW-140)
- **Custom PCB**
- **3D-printed housing**

## Software Components
- Arduino IDE and OpenPLC Editor
- OpenPLC Standard for pin mappings
- Custom Arduino sketches for PLC logic

## Installation

### Hardware Setup
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/Prince-sakariya/Mini-PLC-Project.git
   cd Mini-PLC-Project

2. **Assemble the PCB:**
   - Follow the schematics in the `PCB Schematics` directory.
   - Solder components as per the design.

3. **3D Print the Housing:**
   - Use the STL files in the `Fusion 360 - Housing` directory to print the housing.
   - Assemble the housing with the PCB and Arduino.

### Software Setup
1. Install OpenPLC, visit the [Autonomy Logic Downloads Page](https://autonomylogic.com/download).
2. Follow the [documentation](https://autonomylogic.com/docs/openplc-overview/) to program the Arduino.

## Usage
1. **Connect Sensors and Actuators:**
   - Connect your input devices (sensors) to the input channels.
   - Connect your output devices (actuators) to the output channels.

2. **Power the PLC:**
   - Connect a suitable power supply (5-30V) to the system.

3. **Operate the PLC:**
   - The Arduino will handle input signals and control the output channels according to the programmed logic.

## Schematics and PCB Design

- The complete schematics and PCB design files are available in the `PCB Schematics` directory.
- Use Altium Designer or any compatible software to view and modify the design.

## 3D Printed Housing

- STL files for the housing are available in the `Fusion 360 - Housing` directory.
- Use any standard 3D printer to create the housing parts.

## Documentation
- Detailed project report and user manual are available in the `Documentation` directory.
- [Report_Mini-PLC_Team1.pdf](Documentation/Report_MiniPLC_Team1.pdf)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Special thanks to our supervisors, Prof. Dr. -Ing. Florian Mühlfeld and M. Eng. Fabian Dax, for their guidance and support.
- Kudos to the project team: Prince Sakariya, Kuldeep Mangaroliya, Dhruvin Vekariya, Tejas Shastry, Shardul Joshi, Vaibhav Gujarati.

---

Feel free to reach out for any questions or support!

![GitHub Stars](https://img.shields.io/github/stars/Prince-sakariya/Mini-PLC-Project?style=social) ![GitHub Forks](https://img.shields.io/github/forks/Prince-sakariya/Mini-PLC-Project?style=social)
