# Chip8-emulator
CHIP-8 is an interpreted programming language, developed by Joseph Weisbecker made on his 1802 Microprocessor.  This repo contains code to emulate this system on modern computers.


 key characteristics of CHIP-8:
 - **Memory**: The CHIP-8 VM has 4KB of RAM, which is used to store both the program and the data used by the program.
- **Registers**: There are 16 8-bit registers (V0 to VF). Some of these registers have specific purposes, such as VF, which serves as a carry flag. 
- **Stack**: CHIP-8 has a 16-level stack to call subroutines and manage program flow.
 - **Timers**: There are two timers in the VM - a delay timer and a sound timer. The delay timer is typically used for timing game events, while the sound timer can be used to generate simple sound effects.
- **Graphics**: CHIP-8 has a 64x32 pixel monochrome display, which is used for rendering graphics.
- **Input**: The system has a HEX-based keypad with 16 keys (0 to F), which is used to provide input to the programs.
- **Instruction** set: CHIP-8 has a simple instruction set of 35 different opcodes, allowing basic operations like arithmetic, logic, and drawing on the screen.


My code takes as input a ROM file (extension .ch8) and allows the user to play the game on their system.

ROMS can be found [here](https://github.com/kripod/chip8-roms/tree/master/games).
