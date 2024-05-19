## v6502 Homebrew WDC 65C02 Based Single Board Computer

**PCB 3D View**

<p align="center"> <img src="./ext/pcb.png> </p>

**PCB Route**

<p align="center"> <img src="./ext/route1.png> </p>

**Schematic**

<p align="center"> <img src="./ext/schm1.png> </p>

## Specs
- WDC 65C02 CPU @1.8432MHz
- Altera EPM 7128 CPLD System Controller
- Atmel 28C256 Read-Only Memory (16KB ONLY!)
- Hitachi 62256 SRAM (18KB ONLY!)
- 2x 65C22 VIA (8-bit two way each)
- 2x 65C51 ACIA (2x UART)
- External Bitmap-Text Based VGA Framebuffer

*For more info about VGA Framebuffer, please refer my VGA_Framebuffer Repo: "LINK"

## Memory Hiearchy

## File Locations
PCB Design (KICAD) => ```/pcb```<br>
System Controller  => ```/cnt```<br>
WOZMON OS (ASM)    => ```/os```<br>     
VGA Framebuffer    => ```/vga```<br>
