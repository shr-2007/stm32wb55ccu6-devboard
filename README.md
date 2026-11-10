# STM32WB55CCU6 Development Board

**A custom four-layer STM32WB55CCU6 development-board design by Canal Star Tech.**

> **Project status:** V1.0 PCB design completed; fabrication and electrical validation pending.

![Front 3D render](Images/PCB_3D_Front.png)

## Overview

This repository contains the independently recreated and developed hardware design for a custom development board based on the STMicroelectronics STM32WB55CCU6 wireless microcontroller.

The project explores schematic capture, component selection, USB-C interfacing, 3.3 V power regulation, clock circuitry, SWD programming access, UART connectivity, RF interfacing and four-layer PCB layout using KiCad.

The schematic and PCB were recreated independently. Phil's Lab's STM32 Bluetooth hardware-design tutorial was used as an educational reference; the component placement, PCB routing and board presentation in this repository are this project's own design work.

## Main features

- **MCU:** STM32WB55CCU6
- **USB:** USB Type-C receptacle
- **Power:** 5 V USB input and 3.3 V regulation
- **Regulator:** MIC5366-3.3YC5
- **Clock sources:** 32 MHz HSE and 32.768 kHz LSE
- **Debug/programming:** SWD interface and BOOT switch
- **Serial:** UART header
- **RF:** External RF connector footprint; dedicated PCB antenna planned for V2.0
- **EDA:** KiCad
- **PCB:** Four copper layers

## PCB stackup

| Layer | Assigned net/function |
|---|---|
| F.Cu | GND |
| In1.Cu | GND |
| In2.Cu | 3V3 |
| B.Cu | 3V3 |

This table records the current design intent. Confirm the final fabrication stackup and copper weights with the selected manufacturer before ordering.

## Repository contents

| Directory/file | Contents |
|---|---|
| `Hardware/KiCad/` | Native KiCad schematic, PCB and project files |
| `Hardware/PDF/` | Schematic and other exported PDFs |
| `Hardware/Gerber/` | Fabrication outputs, when generated |
| `Documentation/` | Design notes, BOM and validation records |
| `Images/` | PCB renders and project images |
| `LICENSE` | CERN-OHL-S-2.0 license text |
| `LICENSES/` | Third-party attribution notes |

## Design status and limitations

V1.0 is a PCB design prototype. The board has **not yet been manufactured or electrically validated**. In particular, power-up, USB operation, SWD programming, clock startup, RF performance and Bluetooth functionality remain to be tested on assembled hardware.

A dedicated PCB antenna implementation and associated RF validation are planned for V2.0. The V1.0 external RF connector/footprint should not be interpreted as proof of a validated RF path.

## Future work — V2.0

- Dedicated PCB antenna design and RF matching network.
- RF layout review, impedance planning and validation.
- PCB fabrication and assembly.
- Power-rail and current-consumption measurements.
- Clock startup and accuracy checks.
- USB and SWD bring-up.
- UART and GPIO verification.
- Bluetooth Low Energy testing.

## Acknowledgements

Phil's Lab's STM32 Bluetooth hardware-design tutorial was used as an educational reference:

https://youtu.be/PlXd3lLZ4vc

The schematic capture, component placement, PCB layout, routing and Canal Star Tech branding in this repository were independently recreated and developed for this project.

## License

The original hardware design files explicitly covered by this project are licensed under **CERN Open Hardware Licence Version 2 — Strongly Reciprocal (CERN-OHL-S-2.0)**. See [`LICENSE`](LICENSE) and [`Hardware/NOTICE.md`](Hardware/NOTICE.md).

Third-party components, manufacturer documentation, trademarks and externally sourced library assets remain subject to their respective terms. See [`LICENSES/Third_Party_Attributions.md`](LICENSES/Third_Party_Attributions.md).

**SPDX-License-Identifier:** `CERN-OHL-S-2.0`
