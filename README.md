Computer engineering course 
includes: 
1) Boolean logic 
2) ALU (arithmetics)
3) Memory
4) Machine language
5) Assembler


Short breakdown of each module: 
1. Boolean logic 

Any logic operation can be presented by only one logic gate (chip) called __nand__

![Electrical scheme of nand operator](https://mathcenter.oxford.emory.edu/site/cs170/nandFromTransistors/nand_gate.jpg)

__Nand__ inverts result of __and__ operation 

In the first module were implemented following chips:
 - __Not__ - inverts the value of operand (1 nand)
 - __And__ - returns result of multiplication between 2 operandes (2 nands)
 - __Or__ - returns result of addition of operandes (3 nands)
 - __Xor__ - returns 1 only if both operandes have different values (4 nands)
 - __Mux__ - chooses on of the inputs depending on controlling value (sel) and sends its value
 - __DMux__ - sends a value in one of the outputs depending on controlling value (sel)

It is essential to create a chip using a least amount of nands.