# Aliases

> [CURLY BRACES + WILDCARDS](008_Curly_braces_and_Wildcards.md) --- [HOME](../README.md) --- [TILDE EXPRESSION + STARTUP SCRIPT](010_Tilde_expression_and_Startup_scripts.md)

* Alias is nothing but shortcut to commands.
* **alias** command display list of all alias.
* Add user-defined aliases to **.bashrc**

To create an alias for a command
```
alias aname="COMMAND"
```

To remove the alias
```
unalias aname
```

To remove all alias definition
```
unalias -a
```

### Ignoring an alias
```
\COMMAND
"COMMAND"
```
> Another way to ignore alias is to use full path.

### How to permanently alias?

1. Store alias in **/rtc/bashrc** or **/etc/profile.d/useralias.sh**
2. User-specific alias can be placed in **.bashrc**

> We need to create the useralias.sh file.