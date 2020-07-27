# Curly braces and Wildcards

> [LOCATING COMMANDS](007_Locating_commands.md) --- [HOME](../README.md) --- [ALIASES](009_Aliases.md)

## Recalling History

* BASH keep command history in buffer or a default **.bash_history**
* history buffer can store various commands and can be accessed using **history** command.
* **history** command display history list and command number.

## Curly Braces

* **Curly Braces {}** expands to create patterns.
* Saves command typing time.
* Generates arbitary string.

```
echo I like {d,t,a}
-> I like d t a
echo file{1,2,3}.txt
-> file1.txt file2.txt file3.txt
echo file{1..3}.txt
-> file1.txt file2.txt file3.txt
```

## Wildcards

1. \* : Matches any string (inclusing null string).
2. \? : Matches any single (one) character.
3. [..] : Matches any one of enclosed character.