# Executing a Shell Script

> [COMMENTS IN SHELL](006_Comments_in_Shell.md) --- [HOME](../README.md) --- [DEBUGGING A SHELL SCRIPT](008_Debugging_a_Shell_Script.md)

First, we need to add execution permission to our script which can be achieved using,
```
chmod +x SCRIPTNAME
```

> To read more about permissions, use the command  ```man chmod```

Further, run the script using,
```
./SCRIPTNAME
```

------------------------------------

Also, we can run the script directly, without adding execution permission to the script using,
```
bash SCRIPTNAME
```
> Here, the bash interpretor is specified.

We also have another way of executing the shell script, for it we also don't require execution permission.
```
. SCRIPTNAME
```
Here we are using .(dot command), which reads and execute command from the file in current shell.