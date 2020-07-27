# Tilde Expression and Startup Scripts

> [ALIASES](009_Aliases.md) --- [HOME](../README.md) --- [BASH PROMPT](011_BASH_Prompt.md)

## Tilde(~) Expression

**tilde (~)** may be used refer to own home directry.

1. **~ :** Home directory
2. **~+ :** Present working directory
3. **~- :** Last working directory

## Startup Scripts

1. **/etc/profile** file contains linux's systemwide environment and startup programs. Runs first when user logs in. Acts as systemwide profile for BASH.
2. **/etc/profile.d** directory is called by */etc/profile*. It is a directory and all scripts in this directory are called by /etc/profile.
3. **.bashrc** and **.bash_profile** explained well in [BASH STARTUP SCRIPT](002_BASH_Startup_File.md).