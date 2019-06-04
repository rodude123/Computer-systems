# ALU and CPU

## Control unit
  * The control unit obtains data / instructions from memory
  * Interprets / decodes the instructions into commands / signals
  * Controls transfer of instructions and data in the CPU
  * Coordinates the parts of the CPU
  
## Registers
  *
  
## ALU
  * Does all the mathematical processing of the CPU
  * It is made from CMOS transistors
  * The input consists data and control
  * Usually contains multiple data inputs e.g. A and B
  * Performs AND  OR XOR additon substractions and comparison
  * The set of ALU opertations is part of the microarchitecture of the computer
  * Performs one operation at a time
 
 
 ## FDEC
 CPU operates in a cycle
   * Fetch an instruction from the memory locationn of program counter
   * execute instruction
   * update program counter
 
 An instruction may:
   * Transfer dta between main memory and a register
   cause the ALU or arithmetic operation on data in registers
   * Change the program counter
   
CPU obeys it's instruction set
  
## Binary addition

XOR gate

|A|B|Z|
|-|-|-|
|0|0|0|
|1|0|1|
|0|1|1|
|1|1|0|

