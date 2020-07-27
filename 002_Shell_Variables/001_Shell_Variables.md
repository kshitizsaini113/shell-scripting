# Shell Variables & Environment

> [HOME](../README.md) --- [ECHO VS PRINTF](002_echo_vs_printf.md)

Variables are used to store data and configuration option.
There are two types of variables :
1. System Variables
2. User-Defined Variables

* **System Variables :** Created and maintained by Linux BASH. Usually defined in Capital Letters.

Any of the these command can be used to check for existing system variables.
```
set
env
printenv
```

Some important System Variables:

|||
|-------------|-------------|
|BASH_VERSION|Version of BASH|
|HOSTNAME|Name of our device|
|CDPATH|Search path for cd command|
|HISTFILE|File where history is stored|
|HISTFILESIZE|Maximum lines in history file|
|HISTSIZE|Number of commands to remember for history|
|HOME|Current user's home directory|
|PATH|Search path for command|

* **User-Defined Variable :** Created and maintained by user. It is suggested to avoid a variable name wilth all uppercase.

    Notation to be followed to assign value to a vriable.
    ```
    variableName=value
    ```

## Variable Naming Convention

1. Variable name must begin with alphanumeric character or underscore (**_**) symbol.
2. Don't put space on either side of **=** symbl.

> We can also define null variable in BASH using the notation below,
```
variableName=
variableName=""
```

## Some special variables

```
declare -TYPE variable=value
```

Here type can be of two type,

1. **i** <-> Integer Variable
2. **r** <-> Readonly Variable