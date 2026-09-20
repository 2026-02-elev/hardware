# CellGuard Hardware

Hardware repository for the **CellGuard** prototype.

This repository contains the PCB design source, manufacturing previews, and bill of materials used for the current low-voltage cell / supercapacitor test hardware.

## Repository contents

- `ProPrj_CellGuard_Test_2026-09-16.epro2` — PCB / schematic project source
- `PCB1_Gerber_Front_Back.pdf` — front/back fabrication preview for PCB 1
- `PCB2_Gerber_Front_Back.pdf` — front/back fabrication preview for PCB 2
- `통합_BoM_가격표.md` — consolidated bill of materials and prototype cost

## Hardware snapshot

The current prototype uses components including:

- 2.7 V / 5 F supercapacitors for low-energy cell emulation
- NTC thermistors
- PC817C optocouplers
- SRD-05VDC-SL-C relays
- AO3400A / AO3401A MOSFETs
- ULN2803A driver
- 74HC595 shift register
- REF3025 voltage reference
- MP1584EN buck modules
- charge/discharge resistors and protection components

## Status

PCB design and the prototype BOM are under active iteration for the 2026 project.

The PDF files are provided as inspection previews. Fabrication should use the original PCB project / exported manufacturing files after a final electrical, footprint, and connector-pinout review.

## Safety

This is experimental hardware. Verify component ratings, polarity, current limits, clearances, connector pinout, and power sequencing before applying power.

Supercapacitors must remain within their rated voltage and should be operated with appropriate current limiting and protection.
