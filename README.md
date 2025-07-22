# M.2 to OCulink adapter

Copyright (c) 2025 [Antmicro](https://www.antmicro.com)

![](img/m2-oculink-adapter-render.png)

## Overview

This board is an M.2 to OCuLink adapter that passively connects all x4 lanes available to the M.2 connector to the OCulink socket.

## Key features

- Compatible with the Jetson Orin Baseboard
- Exposes 4 lanes of PCIe via an OCuLink connector
- 2 connectors: M.2 (Key M) and OCulink (Amphenol_G14A421211112HR)
- 0R resistor on 3.3V rail, nPERST, nWAKE, nCLKREQ, and PCIe reference clock signal
- Test points:
    * TP1 connected to nPERST
    * TP2 connected to nWAKE signals
- Compatible with 22mm x (42/60/80)mm form factor

## License

This project is licensed under the [Apache-2.0](LICENSE) license.
