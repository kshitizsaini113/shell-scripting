# Comments in Shell

> [BASIC VI COMMANDS](005_Basic_vi_commands.md) --- [HOME](../README.md) --- [EXECUTING A SHELL SCRIPT](007_Executing_a_Shell_Script.md)

* A line begining with # causes that line to be ignored.
* It is nothing but explanatory text about script.
* It makes source code easier to understand.
* Helps others to understand the code, to help to modify the script.

> Shebang is not considered to be comment, instead it is completely different as explaied.

```
#!/bin/bash
echo "Kshitiz here"
#I am printing my name
```

### Multiple Line Comment

To create a multiple line comment, we use, 
```
#!/bin/bash
echo "Kshitiz Here
<<COMMENT_NAME 
Multi-Line Comment
Again a comment
COMMENT_NAME
echo "Comment Finished"
```

