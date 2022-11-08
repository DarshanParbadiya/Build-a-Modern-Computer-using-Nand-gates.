# Build-a-Modern-Computer-using-Nand-gates.
build a complete functioning computer that can run anything including games using only one of the elementary logic gates called Nand gate. To learn how computer actually works even from the circuit level.

Designed Architecture for HACK computer and CPU along with Logic gates, Adders, multiplexers, memory units, ALU and RAM units for computer. Developed machine language for this computer. Lastly, created an assembler using higher level language for this computer.

For building this general-purpose computer, required chips were designed using HDL (hardware descriptor language). For example, hardware engineers also use hardware simulator to design chips for computer. This way I was able to learn how to make computer chips along with debugging the problems which occurs while designing them. Learnt why only binary language used for computers, how to make different elementary gates using NAND gate, then used those gates and made Adders, ALU, Registers and RAM memory chips, counters for computer. Followed by this, I developed CPU using above chips and machine instructions for this CPU. In next step Implemented screen of this computer using screen memory map, here by manipulating Bits in this memory we can change pixels of screen. Now then everything was ready so, last part was to combine everything that I made to make final usable computer using Von Neumann Architecture. Since this computer works only on binary language, it was a tedious task to write program for that. Finally wrote an assembler for this binary language. Keyboard of this computer works on ASCII code and it is implemented using Keyboard memory map.

Project 1: Building elementary logic gates like And, Or, Not, Multiplexor, and more

Project 2: Building a family of adder chips, culminating in the construction of an Arithmetic Logic Unit (ALU)

Project 3: Building registers and memory units, culminating in the construction of a Random Access Memory (RAM)

Project 4: Learning a machine language and using it to write some illustrative low-level programs

Project 5: Using the chipset built in projects 1-3 to build a Central Processing Unit (CPU) and a hardware platform capable of executing programs written in the machine language introduced in project 4

Project 6: Developing an assembler, i.e. a capability to translate programs written in symbolic machine language into binary, executable code.

**Using an Assembler:**

In order to use the assembler run:
`python assembler.py <target>`.

The target needs to be a ".asm" file and the output will be a ".hack" file

To test the assembler load both the target file and the output of running the
assembler with the target file to the Assembler (tool provided), then the
Assembler will compare the the suplied output is valid.

