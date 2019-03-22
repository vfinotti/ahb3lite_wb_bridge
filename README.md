# AHB-Lite Wishbone Bridge

This repository contains a soft IP bridge between the [AMBA 3 AHB-Lite v1.0 ](http://infocenter.arm.com/help/topic/com.arm.doc.ihi0033a/index.html) and [Wishbone Version B4](http://cdn.opencores.org/downloads/wbspec_b4.pdf) bus protocols, written in Verilog.


## Features

- Tested through simulation and synthesis
- Support for AMBA 3 AHB-Lite and Wishbone version B4 protocol
- 32-bit width address bus
- 32-bit width data bus
- Common clock and reset (active low) signals

## Interfaces
- AHB3-Lite master to Wishbone slave interface
- Wishbone master to AHB3-Lite slave interface
