# ISAP-1.5 computer Block Diagram
The ISAP-1.5 Computer is the improved version of the ISAP-1 computer made by me.

ISAP Computer stands for Improved Simple as Possible Computer.

This is the first stage of the design of the ISAP-1.5 Computer and consists of the process of optimizing the functionality of the ISAP-1 computer at the Block Diagram level.

By: Lincă Marius Gheorghe,

Pitești, Argeș, Romania, Europe.

https://github.com/LincaMarius

## About the project, brief description
The goal of this project is to create a more efficient version of the ISAP-1 (Simple As Possible) computer with minimal modifications, which has instructions encoded in 8 bits.

The second condition is that the Program Counter remains 8 bits.

## ISAP-1.5 version 1.0
The Block Diagram of the ISAP-1 Computer is shown in the following figure:

![ Figure 1 ](/Pictures/Figure1.png)

The Block Diagram of the ISAP-1 Computer Central Processing Unit is shown in the following figure:

![ Figure 2 ](/Pictures/Figure2.png)

### 8-bit Program Counter Implementation
The first condition that must be met by the ISAP-1.5 computer structure is to have an 8-bit Program Counter.

For this purpose, the Program Counter is implemented on 8 bits. Thus, when the EP control signal is activated, the Program Counter will write an 8-bit numerical value to the Data Bus.

The Address Register is also 8 bits and by default the Address Bus will be 8 bits.

The ISAP-1.5 Central Processing Unit can directly address 2^8 = 256 addresses.

The second condition is that the instructions are encoded on 8 bits. So the operand is no longer part of the instruction so the Instruction Register no longer has to put data on the Data Bus, as a result we have also eliminated the EI control signal.

Following these changes, the Block Diagram of the ISAP-1.5 Computer Central Processing Unit is presented as follows:

![ Figure 3 ](/Pictures/Figure3.png)