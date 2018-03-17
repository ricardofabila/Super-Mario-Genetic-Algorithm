# Super-Mario-Genetic-Algorithm
A Genetic Algorithm implemented in Lua to beat the first level os the classic Super Mario for NES.

This Genetic Algorithm finds a correct jump sequence that can beat the first level of the game.

Each sequence is seen as a string of 1's and 0's eg. 1111100000011111000011110011....

Each 1 is a jump and a 0 is no input (no jump). The game is set to always move to the right.

To try this script you will need:

**BizHawk Emulator**
**The Super Mario Bros. ROM for the SNES**
**A saved state file of the beginning of the first level (you can make one with BizHawk) named "SMB1-1.state"**

You need to open the rom file, then go to scripts and load the lua file. The game state must be on the same directory as the Lua file. I recommend creating a folder inside the BizHawk folder with the rom, the state file, and the script.

