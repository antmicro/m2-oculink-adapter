# M.2 to OCuLink adapter

Copyright (c) 2025 [Antmicro](https://www.antmicro.com)

![](img/m2-oculink-adapter-render.png)

## Overview

This project includes PCB design files that define a simple M.2 (key-M) to OCuLink adapter that can be used for connecting PCIe lanes from on-board M.2 slots with remote PCIe devices via OCuLink cables. 
This board has been designed to be compliant with Antmicro [Jetson Orin Baseboard](https://github.com/antmicro/jetson-orin-baseboard) if you plan to use it with other pieces of hardware please inspect the schematics and connection diagrams beforehand. 
The PCB design files were prepared in KiCad 9.x.

## Key features

- Compatible with the Jetson Orin Baseboard
- Exposes 4 lanes of PCIe via an OCuLink connector
- M.2 Key M
- OCulink connector (Amphenol G14A421211112HR)
- Compatible with  2280, 2260, 2242 M.2 mechanical form factors

## License

This project is licensed under the [Apache-2.0](LICENSE) license.
