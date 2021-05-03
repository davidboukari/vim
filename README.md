# vim


## Create file from .swp

```bash
vim -r .file.swp
```

## Search in Forward/Backward
```
* press ?<searchpattern>             
=> n to search backward or N to search forward 
```

## Go to line,column

:call cursor(15,25)

## to lowercase to uppercase
* https://vim.fandom.com/wiki/Switching_case_of_characters
```
Toggle case "HellO" to "hELLo" with g~ then a movement.
Uppercase "HellO" to "HELLO" with gU then a movement.
Lowercase "HellO" to "hello" with gu then a movement.
```
