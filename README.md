# Elf-Cube - Processor card
Simple retro computer based on the 1802 series of processors.

Holds the main CPU, 1 x 32K ROM and 2 x 32K RAM sockets.

After reset, ROM runs from 0x0000 - 0x7FFF and RAM from 0x8000 - 0xFFFF. As soon as an instruction fetch occurs from RAM, the
ROM is replaced with the second RAM chip leaving a full 64K RAM available to user programs.
