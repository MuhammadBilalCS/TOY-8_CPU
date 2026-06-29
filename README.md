# TOY-8_CPU
TOY-8: An educational 8-bit computer created with LogiSim digital circuit simulator

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
<pre>
  ╔════════════════════════════════╗
  ║   ████████╗ ██████╗ ██╗   ██╗  ║
  ║   ╚══██╔══╝██╔═══██╗╚██╗ ██╔╝  ║
  ║      ██║   ██║   ██║ ╚████╔╝   ║ 
  ║      ██║   ██║   ██║  ╚██╔╝    ║ 
  ║      ██║   ╚██████╔╝   ██║     ║ 
  ║      ╚═╝    ╚═════╝    ╚═╝     ║  
  ╚════════════════════════════════╝
  
        ╔════════════════════════════╗
        ║   █████████████████████    ║
        ║   █ 8 and 16-BIT █ CPU█    ║
        ║   █████████████████████    ║
        ╚════════════════════════════╝
</pre>
<p align="center">
  <img src="images/16_BIT_CPU.png" width="1000">
</p>


 # Overview
# Milestone 1 
 *Gates*
1. *NOT* — from transistors
2. *AND* — from transistors
3. *OR* — from transistors
4. *NAND* — from transistors
5. *NOR* — from transistors
6. *XOR* — from transistors
7. *XNOR* — from transistors
8. *3-input AND* (generalized AND) — chain your 2-input ANDs; needed for the adder and decoder
9. *Multi-input OR* (start with 3-input) — chain your 2-input ORs; needed for MAJ/ODD and the mux

*Adder*
10. *Half adder* — 2-input XOR gives sum, AND gives carry (warm-up build)
11. *ODD* (1-bit) — 3-input parity function; this is the sum bit of a full adder
12. *MAJ* (1-bit) — 3-input majority function; this is the carry bit of a full adder
13. *1-bit full adder* — ODD (sum) + MAJ (carry) wired together as one cell
14. *8-bit ripple-carry adder* = your *ADD* module — chain 8 full-adder cells, carry-out → next carry-in

*8-bit logic modules*
15. *8-bit bitwise AND* — your 1-bit AND replicated across 8 bits
16. *8-bit bitwise XOR* — your 1-bit XOR replicated across 8 bits

*Selection circuits*
17. *3-to-8 decoder* — eight 3-input ANDs; exactly one output is hot (one-hot)
18. *3-to-8 demux* — take the decoder, AND each output with a data input X
19. *3-to-8 decoder/demux* — combine the two so each selected output is a pair (1, X)

*ALU (the capstone)*
20. *1-bit one-hot-mux* — AND each function's output with its select line, then OR the results onto one wire
21. *8-bit ALU* — run ADD + 8-bit AND + 8-bit XOR in parallel, then use the one-hot-mux (driven by your decoder) to push the chosen result onto the output bus


22. *Left-shift circuit*
23. *Right-shift circuit*
24. 1-bit one-hot-mux — AND each function's output with its select line, then OR the results onto one wire
25, Full Subtractor
-----------------------------------
## Milestone 2

DFlipFlop 
MemoryBit 
ClockControl
Register 8bit
Register 4bit
Incrementer 4bit
BusMux2way (2-way 4-bit)
PC (program counter)
DecDemux4to16
OneHotMux 16 way 8 bit
MemoryBank (8-bit 16-word)
R_Mux (3-way 8-bit)
AddrMux (2-way 4-bit)
Layout (connect all components you've built so far)





