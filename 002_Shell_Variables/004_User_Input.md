# User Input

> [QUOTING](003_Quoting.md) --- [HOME](../README.md) --- [ARITHMETIC OPERATIONS](005_Arithmetic_Operations.md)

**read** command accept input from the keyboard and assign an input value to the user defined shell variable.

```
read -p "PROMPT" VARIABLE-1 VARIABLE-2 ...
```

### Handling Passwords

**-s** option causes input from terminal not to be displayed on the screen.
```
read -s VARIABLE
```

### Timeout Input

We can timeout read command using **-t** option. It causes read to timeout & returns failure if complete line of input is not read.
```
read -t TIMEOUT -p "PROMPT" VARIABLE
```

## IFS (Internal File Seperator)

By default ifs is set to space or next line.

```
old=$IFS
IFS=:                                               # Changing IFS
pwd="kshitizsaini113:x:0:0:/home:/bin/bash"
read -r login pass uid gid home shell <<< "$pwd"
IFS=$old                                            # Restoring IFS
```