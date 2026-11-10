# Gerber Fabrication Files

This directory contains the exported Gerber and NC drill files for the **STM32WB55CCU6 Development Board (V1.0)**, designed using KiCad.

These files represent the current PCB layout and are intended for fabrication review and manufacturing preparation.

## Layer Mapping

| File | Description |
|---|---|
| `F_Cu` | Front copper layer |
| `In1_Cu` | Inner copper layer 1 |
| `In2_Cu` | Inner copper layer 2 |
| `B_Cu` | Back copper layer |
| `F_Mask` | Front solder mask |
| `B_Mask` | Back solder mask |
| `F_Silkscreen` | Front silkscreen |
| `B_Silkscreen` | Back silkscreen |
| `F_Paste` | Front solder paste |
| `B_Paste` | Back solder paste |
| `Edge_Cuts` | Board outline |
| `PTH.drl` | Plated through-hole drill data |
| `NPTH.drl` | Non-plated through-hole drill data |

## Additional Files

- **Gerber Job File (`.gbrjob`):** Contains fabrication-layer information and metadata.
- **Drill Map PDFs:** Visual references for plated and non-plated drill locations.

## Fabrication Notes

- **Board revision:** V1.0
- **EDA software:** KiCad
- **Layer count:** 4 copper layers
- **Project:** STM32WB55CCU6 Development Board
- **Designer:** Canal Star Tech

The intended copper-layer arrangement is:

1. Front Copper — GND
2. Inner Layer 1 — GND
3. Inner Layer 2 — 3V3
4. Back Copper — 3V3

Confirm the final stackup, copper thickness, board thickness, drill tolerances and manufacturing capabilities with the selected PCB manufacturer before placing an order.

## Important Notice

These files are exported from the current V1.0 PCB design. They have not yet been independently verified by a PCB manufacturer or validated through physical fabrication and assembly.

**Please inspect the Gerber files before manufacturing.** The presence of fabrication outputs does not imply that the board has been manufactured or electrically validated.

---

Part of the STM32WB55CCU6 Development Board project by **Canal Star Tech**.
