# CPU Registers & Tristate Buffers for the SABRINIAC
This project creates the PCBs for my CPU registers and the tristate buffers to I/O with them.

It is for my '60s inspired computer im making base don the Intel 8080. At the time of writing this I have RAM + it's clock done and the ALU Modules done. After I get the registers + buffers I'll only have to make a motherboard and an opcode decoder/microcode

<img width="613" height="571" alt="image" src="https://github.com/user-attachments/assets/6b90ea68-0362-4434-b3ef-51921e532d38" />

How to assemble? Just solder on all of the 2N2222 Transistors (or other NPN transitors) and 0603 1kohm resistors

BOM:

| Part Name | Count |
|-----------|-------|
| Register PCBs | 18 |
| Tri-State Buffer PCBs | 26 |
| 2N2222 NPN Transistors | 1406 |
| 0603 SMD 1kohm Resistors | 2684 |
| Pin headers | Any combination of 1xN Right Angle Male Pin Headers to make up 1x854 |
