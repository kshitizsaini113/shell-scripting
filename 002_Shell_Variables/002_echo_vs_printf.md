# echo vs printf

> [SHELL VARIABLES](001_Shell_Variables.md) --- [HOME](../README.md) --- [QUOTING](003_Quoting.md)

* Both **echo** and **printf** are used to display variable's value.
* By default, echo don't offer  any formatting option, but printf do so.

To enable formatting in echo 
```
echo -e "..."
```

## Formatting Directives

|||
|-------------|-------------|
|\\" |Double Quote|
|\\\ |Backslash|
|\\a |Alert|
|\\b |Backspace|
|\\t |Horizontal Tab|
|\\e |Delete|
|\\c |No further output|
|\\f |Form feed|
|\\n |New line|
|%%  |Single %|

### printf options

```
printf "%w.pL" variableName
```

> w -> Minimum width
>
> p -> Precision count
>
> L -> Convenience character
>> s-> String
>> 
>> d-> Integer
>>
>> e-> Exponential
>>
>> f-> Floating Point