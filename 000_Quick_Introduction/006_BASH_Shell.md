# BASH (Bourne Again Shell)

> [COMMAND LINE](005_Command_Line.md) --- [HOME](../README.md) --- [UNIX PHILOSOPHY](007_Unix_Philosophy.md)

* Command language interpretor for Linux.
* Developed by GNU Project.
* Backward compatible with sh shell.
* Incorporates features from Korn Shell and C Shell.

## Shell Commands
* **Internal Commands :** (Built-in) part of shell itself.
* **External Commands :** Seprate binaries stored in specific directories.

## BASH + Command Types

* Aliases (such as ll)
* Keywords (such as if)
* Functions
* Built-In (such as pwd)
* Files (such as /bin/date)

### type command
Used to find out if a command is built-in or an external binary.
```
type -a COMMAND
```
Returns **built-in**, if the command is internal; Returns **path of command** in case of external.

**Kernel :** Core of any Operating System.

**Shell :** Provide interface b/w User and Kernel.

**Terminal :** Allow users to enter command & display back results.