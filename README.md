# Build-a-Modern-Computer-using-Nand-gates.
build a complete functioning computer that can run anything including games using only one of the elementary logic gates called Nand gate. To learn how computer actually works even from the circuit level.

For building this general-purpose computer, required chips were designed using HDL (hardware descriptor language). For example, hardware engineers also use hardware simulator to design chips for computer. This way I was able to learn how to make computer chips along with debugging the problems which occurs while designing them. Learnt why only binary language used for computers, how to make different elementary gates using NAND gate, then used those gates and made Adders, ALU, Registers and RAM memory chips, counters for computer. Followed by this, I developed CPU using above chips and machine instructions for this CPU. In next step Implemented screen of this computer using screen memory map, here by manipulating Bits in this memory we can change pixels of screen. Now then everything was ready so, last part was to combine everything that I made to make final usable computer. Since this computer works only on binary language, it was a tedious task to write program for that. Finally wrote an assembler for this binary language. 


In order to use the assembler run:
`python assembler.py <target>`.

The target needs to be a ".asm" file and the output will be a ".hack" file

To test the assembler load both the target file and the output of running the
assembler with the target file to the Assembler (tool provided), then the
Assembler will compare the the suplied output is valid.
