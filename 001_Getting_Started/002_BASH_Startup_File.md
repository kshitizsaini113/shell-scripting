# BASH Startup Script

> [BASH SHELL](001_BASH_Shell.md) --- [HOME](../README.md) --- [SHEBANG](003_Shebang.md)

### Login Shell

* Started when we login to system.
* Set environment which is exported to non-login shell.
* Login shell calls the following,
    1. **/etc/profile** run first when we login to the system.
    2. **$HOME/.bash_profile, $HOME/.bashrc & $HOME/.profile** runs second when user logs in. The files run in the specified order. *$HOME/.bash_profile calls $HOME/.bashrc which calls /etc/bashrc.

### Non-Login Shell

* When non-login shell is started, bash read and execute commands from **/etc/bash.bashrc or /etc/bashrc and $HOME/.bashrc**.
* *First it calls **$HOME/.bashrc** which calls **/etc/bash.bashrc** which calls **/etc/profile.d**.*

### BASH Logout Script

* When login script exits, bash reads and executes command from **$HOME/.bash_logout**.
