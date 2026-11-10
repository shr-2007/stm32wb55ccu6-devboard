# Third-Party Attributions

This project uses selected third-party components, manufacturer documentation, EDA libraries and 3D models. Their respective owners retain their intellectual property rights. These materials are not automatically relicensed under CERN-OHL-S-2.0.

| Resource | Manufacturer / Source | Usage |
|---|---|---|
| STM32WB55CCU6 | STMicroelectronics | Main wireless microcontroller |
| MIC5366-3.3YC5 | Microchip Technology | 3.3V voltage regulator |
| DLF162500LT-5028A1 | TDK Corporation | 2.4–2.5 GHz RF low-pass filter |
| UART connector 3D model | KiCad library / original model source to be confirmed | 3D PCB visualization |
| KiCad | KiCad Development Team | Schematic capture and PCB design |

## Component Documentation

### TDK DLF162500LT-5028A1

- Manufacturer: TDK Corporation
- Component: Multilayer low-pass RF filter
- Frequency range: 2400–2500 MHz
- Package: 1.6 × 0.8 mm (0603)
- Number of terminals: 4

Official datasheet:

https://product.tdk.com/info/en/documents/data_sheet/rf_lpf_dlf162500lt-5028a1_en.pdf

### UART Connector 3D Model

| UART Connector | Molex PicoBlade 53048-0410 | 4-pin, 1.25 mm pitch, right-angle, through-hole connector |
| UART Connector Footprint | KiCad Official Footprint Library – Connector_Molex | Standard KiCad footprint |
| UART Connector 3D Model | KiCad Official 3D Model Library – Connector_Molex.3dshapes | Standard KiCad STEP model |

## KiCad Libraries and 3D Models

## KiCad Libraries and 3D Models

The following standard KiCad libraries and associated 3D models were used in this project:

| Asset | Source | License |
|---|---|---|
| Symbols | KiCad Official Libraries | KiCad Library License |
| Footprints | KiCad Official Footprint Libraries | KiCad Library License |
| 3D Models | KiCad Official 3D Model Libraries | KiCad 3D Model License |

### Specific Components
- **UART Connector:** `Molex_PicoBlade_53048-0410_1x04_P1.25mm_Horizontal` — KiCad Connector_Molex footprint library.
- **RF Filter:** TDK DLF162500LT-5028A1 — manufacturer component and datasheet.

All third-party assets retain their respective original licenses and are not relicensed under CERN-OHL-S-2.0.

## Educational Reference

Phil's Lab STM32 Bluetooth hardware-design tutorial was used as an educational reference:

https://youtu.be/PlXd3lLZ4vc

The schematic capture, component placement, PCB layout, routing and Canal Star Tech branding in this repository were independently recreated and developed for this project. No original tutorial project files are intentionally included in this repository.
