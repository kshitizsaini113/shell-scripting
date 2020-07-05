# Debugging a Shell Script

> [EXECUTING A SHELL SCRIPT](007_Executing_a_Shell_Script.md) --- [HOME](../README.md)

To debug a script, we need to run the script as,
```
bash -x SCRIPTNAME
```
or
```
bash -xv SCRIPTNAME
```

We can also modify shebang line to run an entire script in debugging mode.
```
#!/bin/bash -x
```

## Built-in Debugging Commands

BASH offers debugging commands by itself, which can be turned on or off using the set command.

* **set -x ->** Displays command and arguments as they are executed.
* **set -v ->** Displays shell input lines as they are read.
* **set -n ->** Read commands, but don't execute them. Used to check shell script for syntax errors.

```
#!/bin/bash

set -x
# Turning on debugging mode

echo "Kshitiz here"
echo "Debugging Script"

set +x
# Turning off debugging mode
```