# P8D16A_2A

P8D16A_2A is a virtual processor that I designed in (Digital)[https://github.com/hneemann/Digital] for fun.

It currently has a known bug in the microcode where conditional jumps and most instructions that change the Program Counter sometimes result in interpreting the instruction's arguments as more instructions if the jump is not performed.

There is documentation for it, but it is scattered across excel sheets and other documents. Since this project has been abandoned, I will only get the docs together if I have the time.
The microcode builder, assembler and disassembler are similarly scattered, and are merged with the same tools for a differnt processor. Again, they will only be added to this repo if I have the time for that.
