# MIPS16
In this project we\'ve tried to design a 16-bit Pipelined MIPS Processor. The design has been optimized to acheive **Higher Performance**, **Lower Cost**, **Simple** and **Portable** Processor.

## Instruction Set Architecture (ISA)
We've proved that the ISA given by the instructor isn\'t *Turing Complete*. So we redesigned the ISA by adding more instructions without changing the given ISA (so that programs written for the original ISA can be run on our processor). After designing a Turing Complete ISA, some opcodes wasn\'t reserved, so we added other instructions to increase the performance, these instructions were chosen to be commonly used in the programs, and need many primitive instructions to be evaluated.

## Testing and Validating
We\'ve created four testcases, two of them targeted the logical and arithmetic instructions, and the others targeted the control flow instructions. We validate each of them by resetting the processor (all registers and data memory are set to zeros), then running the testcase, and compare the state of the registers and data memory with the expected states.