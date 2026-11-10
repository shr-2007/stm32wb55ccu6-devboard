# Design Notes - STM32WB55CCU6 Development Board

## Project identity

- Project: STM32WB55CCU6 Development Board
- Organization: Canal Star Tech
- Revision: V1.0
- EDA: KiCad
- Status: PCB design completed; fabrication and validation pending
- Hardware license: CERN-OHL-S-2.0

## Design intent

A custom development board built around the STM32WB55CCU6, intended as a learning and hardware-design project. The design includes USB-C power/input, 3.3 V regulation, external clock sources, SWD access, a UART header, boot configuration and an RF connector footprint.

## Functional blocks

1. STM32WB55CCU6 microcontroller.
2. USB Type-C connector and USB protection/interface circuitry.
3. 5 V to 3.3 V regulation using MIC5366-3.3YC5.
4. 32 MHz HSE clock source.
5. 32.768 kHz LSE clock source.
6. SWD programming/debug interface.
7. BOOT switch/configuration.
8. UART header.
9. RF connector footprint.

## PCB stackup intent

| Copper layer | Assigned plane/net |
|---|---|
| F.Cu | GND |
| In1.Cu | GND |
| In2.Cu | 3V3 |
| B.Cu | 3V3 |

Confirm copper weights, dielectric thicknesses, impedance requirements and manufacturer capability against the actual fabrication stackup before production.

## Known limitations

- Board has not been manufactured or assembled.
- Power-up and current consumption have not been measured.
- USB functionality has not been tested.
- SWD programming has not been tested on assembled hardware.
- HSE/LSE startup and accuracy have not been measured.
- RF path, matching and antenna performance have not been validated.
- A dedicated PCB antenna is planned for V2.0.

## Revision history

| Revision | Date | Changes |
|---|---|---|
| V1.0 | 2026-11 | Initial four-layer PCB design and documentation baseline |

Update this file whenever the design changes.
