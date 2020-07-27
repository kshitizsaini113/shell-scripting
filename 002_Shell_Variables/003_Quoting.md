# Quoting

> [ECHO VS PRINTF](002_echo_vs_printf.md) --- [HOME](../README.md) --- [USER INPUT](004_User_Input.md)

### Double Quote (**"**)
Useful when we want variable and command substitution.
```
echo "$SHELL"
-> /bin/bash
```

### Single Quote (**'**)
Turns off special meaning of all character, be it command or variable. Everything will be printed as displayed.
```
echo '$SHELL'
-> $SHELL
```

### Backslash (**\\**)
Removes special meaning of characters in double quotes.
```
echo "\$SHELL = $SHELL"
-> $SHELL = /bin/bash
```

## Unsetting Variables
* **unset** command is ised to delete variable during program execution.
* unset can be used both with variables as well as functions.

The syntax for unset is :
```
unset variableName
```

> Readonly variables can't be unset.