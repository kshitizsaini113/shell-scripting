# Shebang (#!)

> [BASH STARTUP SCRIPT](002_BASH_Startup_File.md) --- [HOME](../README.md) --- [WRITING FIRST SCRIPT](004_Writing_first_script.md)

**#!** syntax is used in scripts to indicate an interpreter for execution under UNIX/Linux Operating System.

**#!/bin/bash**

**#!/usr/bin/env bash**

## Starting script with #!

1. **#!** is called **Shebang** or **bang** line.
2. It is nothing but absolute path of BASH.
3. It conists of #! followed by interpreter's path.
4. All script run on the specific interpretor.
5. Almost all scripts begin with #!/bin/bash.
6. Shebang was introduced Dennis Ritchie.

---------------------------------------------------------

**#!/bin/sh ->** Used for system boot script.

**#!/bin/bash ->** Used for typical scripts.

**#!/usr/bin/env bash ->** Run bash in modified environment. Makes BASH script portable. Uses whichever bash executable appear first in user's PATH.