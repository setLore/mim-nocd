# mim-nocd
Madagascar Island Mania no-CD patch

## How to use
Download the patched .exe from the [releases](https://github.com/setLore/mim-nocd/releases) page and put it in your game directory, replacing the original Madagascar.exe file.

## What does this patch do?
Changes the 0045cb08 instructions from JZ to JMP which skips over the CD check, allowing the game to be launched without being on a CD.

## Tools used
* [Ghidra](https://github.com/nationalsecurityagency/ghidra)
