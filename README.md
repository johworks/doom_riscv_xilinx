Doom classic port to lightweight RISC-V
=======================================

This is a port to try and make adapting/running doom to simple
RISC-V platform easier with the code to adapt well split.

A buildable original linux-x11 version will hopefully kept to be
able to test things locally a bit easier.

---

The original project wrote the RISC-V code with the target of the ICE40
FPGA. I have modified the code to work with Xilinx Vivado IPs.

I plan to change all the files in the riscv directory that start with i_*.

