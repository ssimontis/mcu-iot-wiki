# Microcontrollers

* Consists of an instruction set \(and HW to carry out instruction set commands\), memory and registers
* Each instruction set command is represented by an assembly language construct
* Memory is also used to store the program code to be executed
  * Upon reset, the MCU begins executing instructions at some fixed address
  * Program Counter is initialized to the Reset Vector, a starting address which triggers the first instruction of the program to be loaded
  * PC is increased by sizeof\(instruction\) after loading instruction to represent the next value that will be requested from memory to continue program execution
  * Process repeats forever until power is turned off for microcontroller
* RISC processors have advantage of fixed-length instructioins
  * Some CISC architectures have variable-length commands, and length of next command is not immediately known until decoding of instruction begins

