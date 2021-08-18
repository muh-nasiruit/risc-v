# Microprocessor and Assembly language
Basic RV32I processor circuit with implementation of a few R-Type operations.

## Dependancy
1. Download and Install Logisim from [Here](https://logisim.en.uptodown.com/windows).
2. Open the file with circuit extension(.circ).

## Operations
The processor is able to perform **ADD, OR, and, AND** instructions.

## Instructions
1. Run Logisim and open the file ``processor.circ``.
2. Set the bits connecting to the ADD block to binary 4 (0100).
3. Enter the machine code for the instruction in the IMEM (Instruction Memory).
4. Set the selector pin according to the required instruction. (00 = ADD, 10 = AND, 11 = OR)
5. Enter the register file and enter values for the registers being used in the machine code.
6. Give the PC counter a clock and check output.

