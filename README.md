# CPU Registers & Tristate Buffers for the SABRINIAC
This project creates the PCBs for my CPU registers and the tristate buffers to I/O with them.

It is for my '60s inspired computer im making base don the Intel 8080. At the time of writing this I have RAM + it's clock done and the ALU Modules done. After I get the registers + buffers I'll only have to make a motherboard and an opcode decoder/microcode

<img width="613" height="571" alt="image" src="https://github.com/user-attachments/assets/6b90ea68-0362-4434-b3ef-51921e532d38" />
<img width="1169" height="816" alt="image" src="https://github.com/user-attachments/assets/539c44fa-c0fe-4d44-be53-ded57a7caebd" />
<img width="1078" height="613" alt="image" src="https://github.com/user-attachments/assets/d52738cd-6331-4200-a8a6-7528cd3a0767" />


How to assemble? Just solder on all of the 2N2222 Transistors (or other NPN transitors) and 0603 1kohm resistors

BOM:

| Part Name | Count | Link | Cost |
|-----------|-------|------|------|
| Register PCBs | 18 | From JLCPCB | $10.20 |
| Tri-State Buffer PCBs | 26 | From JLCPCB | $13.30 |
| 2N2222 NPN Transistors | 1406 | https://www.aliexpress.us/item/3256806831821651.html | $15 |
| 0603 SMD 1kohm Resistors | 2684 | https://www.aliexpress.us/item/3256805937811409.html | $12.56 |
| Pin headers | Any combination of 1xN Right Angle Male Pin Headers to make up 1x854 | I already have them but something like this: https://www.aliexpress.us/item/3256803319359683.html | $3 |
| Total | - | - | ~$70 |
