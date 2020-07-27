# BASH Prompt

> [TILDE EXPRESSION + STARTUP SCRIPT](010_Tilde_expression_and_Startup_scripts.md) --- [HOME](../README.md)

We can customise promot by editing PS1 variable.

|Variable|What it does?|
|-------------|-------------|
|\\d|Day -- dd mm yy|
|\\h|Hostname|
|\\j|Number of jobs managed|
|\\t|24hr time -- hh:mm:ss|
|\\T|12hr time -- hh:mm:ss|
|\\@|12hr time AM/PM|
|\\A|24hr time hh:mm|
|\\u|Username|
|\\W|Current working directory|
|\\!|History number of commands|
|\\$|$ or #|
|\\#|Command number of command|

### Color coding for shell

|Text Format|Foreground Color|Background Color|
|-------------|-------------|-------------|
|0: Normal Text|30: Black|40: Black|
|1: Bold|31: Red|41: Red|
|4: Underline|32: Green|42: Green|
||33: Yellow|43: Yellow|
||34: Blue|44: Blue|
||35: Purple|45: Purple|
||36: Cyan|46: Cyan|
||37: White|47: White|

## PROMPT_COMMAND variable
If PROMPT_COMMAND variable is set, the value is executed as BASH command prior to issuing each primary prompt.
```
PROMPT_COMMAND="COMMAND"
```