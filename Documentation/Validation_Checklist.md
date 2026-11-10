# V1.0 Validation Checklist

Do not mark an item complete until it has been checked on the actual design or assembled hardware.

## CAD and fabrication review

- [ ] KiCad schematic ERC reviewed and saved
- [ ] KiCad PCB DRC reviewed and saved
- [ ] All intended nets routed; unrouted count checked
- [ ] Copper zones refilled and inspected on every layer
- [ ] Board outline and mechanical dimensions checked
- [ ] Drill sizes, annular rings and clearances checked against manufacturer rules
- [ ] Silkscreen checked for pad/mask overlap and readability
- [ ] Fabrication outputs generated and independently inspected
- [ ] Final stackup confirmed with manufacturer

## Hardware bring-up (after fabrication)

- [ ] Visual inspection and continuity checks
- [ ] Resistance checks between power rails and GND before power-up
- [ ] 5 V input verified
- [ ] 3.3 V rail verified
- [ ] Current consumption recorded
- [ ] SWD connection and programming verified
- [ ] BOOT behavior verified
- [ ] UART verified
- [ ] USB enumeration/data operation verified
- [ ] HSE startup verified
- [ ] LSE startup verified
- [ ] RF path and antenna/matching network reviewed
- [ ] BLE operation tested

Record instruments, test conditions, firmware revision, measurements and results before publishing validation claims.
