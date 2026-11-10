# Power Architecture

## Intended power path

USB Type-C VBUS (nominal 5 V input) feeds the MIC5366-3.3YC5 regulator, which generates the nominal 3.3 V rail for the MCU and other circuitry.

## Review items

- Verify regulator input/output capacitor values and placement against the exact MIC5366 datasheet.
- Confirm the expected maximum load and regulator thermal dissipation.
- Check USB-C CC resistor values and orientation for a USB 2.0 sink/device implementation.
- Verify ESD protection placement and device suitability.
- Confirm all MCU power pins, analog supply pins, RF supply pins and VBAT connections against the STM32WB55 datasheet and reference design.
- Check power-plane connectivity, return paths and decoupling placement.

The architecture describes design intent only. It is not a report of measured or validated performance.
