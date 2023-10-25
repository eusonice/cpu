# CPU

## Spec:
> The full spec can be read [here](https://cs61c.org/sp22/projects/proj3/).

A CPU that runs actual RISC-V 32-bit ISA instructions, using Venus and Logisim.  

## Notes: 
My CPU supports the following:
- a datapath that includes ALU, RegFile, Immediate Generator, Branch Comparator, DMEM, etc, to support different types of instructions.
- control logic is created using ROM, for less wiring
- 2 stage pipeline
- handles control hazards when branching with control logic signal and no-op that flush the pipeline
