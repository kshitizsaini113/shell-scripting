# What is Linux Shell?

> [WHAT IS LINUX SHELL](003_What_is_Linux_Shell.md) --- [HOME](../README.md) --- [COMMAND LINE](005_Command_Line.md)

* **Terminal :** GUI based login system.
    
    X Term -> X Terminal

    G Term -> Gnome Terminal

    K Term -> KDE Terminal

* **Connecting via SSH :** We get shell prompt as we login remotely.

* **Using console :** Text-based login.

## How to find current Shell name?

```
$cat /etc/shells
```
Lists all the available shells in our Linux distribution.

#### How to list the current shell?
* echo $SHELL
* ps $$
* ps -p $$