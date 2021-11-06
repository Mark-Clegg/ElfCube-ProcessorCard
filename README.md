# Elf-Cube - Processor card
Simple retro computer based on the 1802 series of processors.

Holds the main CPU, and 2 x 32K RAM/ROM sockets. Jumpers next to each memory socket select ROM/RAM by connecting the ~MWR line, or tying high pin 27.
Q and ~EF4 are also routed to an additional 6 pin connector for bit banged serial support. (EF4 can be disconnected via a jumper, and also connected to ~interrupt via a jumper)
