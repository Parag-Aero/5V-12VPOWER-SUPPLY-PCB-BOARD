# 12V-24V-POWER-SUPPLY-PCB-BOARD
This PCB is designed as power distribution and regulation module for embedded electronic control systems. The board generates regulated 5 V and 12 V DC supply rails for powering microcontroller-based control units and associated driver circuits, respectively, with a maximum output current capacity of 1.5 A.

Dedicated 3-pin JST connectors are provided for interfacing with the microcontroller unit (MCU) and driver circuitry, ensuring reliable power and signal connectivity.

The design incorporates mounting provisions for heat sinks(TO-220 package) for voltage regulators and power MOSFET to facilitate efficient thermal management during operation.

A cooling fan interface is integrated on the PCB to enhance heat dissipation within enclosed installations. Fan operation is controlled by an MCU-generated control signal routed through the designated JST connector, enabling intelligent thermal management based on system requirements.

Additionally, a 3-pin screw terminal block is provided to distribute regulated 12 V and 5 V DC outputs along with a common ground for external devices and auxiliary circuitry.

## Design Status:
- Fabricated: Yes
- Tested: Yes
- Functional: Yes
- DRC: Contains footprint-related clearance violations from imported vendor footprints

The complete EasyEDA source files are included in this repository for design review, modification, and future development.

Single-layer PCB printing documents are also provided.These files can be used directly for PCB fabrication using toner transfer, photoresist, or other single-layer PCB manufacturing processes.
