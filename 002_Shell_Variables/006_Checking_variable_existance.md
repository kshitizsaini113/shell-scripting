# Checking variable Existance

> [ARITHMETIC OPERATIONS](005_Arithmetic_Operations.md) --- [HOME](../README.md) --- [LOCATING COMMANDS](007_Locating_commands.md)

If the variable is not defined, the script will stop executing BASH command,
```
${varName:?Error, varName not declared or is empty}
```

* Useful for sanity checking
* Script will stop executing if variable is not defined.