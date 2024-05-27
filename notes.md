Von Neumann architecture

### Different parts of a CPU
- Program counter aka Instruction pointer: Tells where to fetch the next instruction
- Instruction decoder: Decodes the instruction
- Data bus: Used to access memory
- General purpose registers: Used to store values that are being computed by the CPU
- ALU: Where the real computation happens

### Addressing modes
- immediate mode: data to access is directly available in the instruction
- register addressing mode: the instruction contains a register where the data to be accessed is stored
- direct addressing mode: the instruction contains the memory address to access
- indexed addressing mode: the instruction contains the memory address and an `index register` number used to offset. On x86 processors
it also contains a `multiplier` used to traverse memory either a byte at a time or a word at a time
- indirect addressing mode: the instruction contains a register that contains the memory address of the data to access
- base pointer addressing mode: same as indirect addressing mode but we also specify a number called `offset` that we add to the address
before using it for lookup
