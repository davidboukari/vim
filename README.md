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


## Split
```
    :sp will split the Vim window horizontally. ...
    :vsp will split the Vim window vertically. ...
    Ctrl-w Ctrl-w moves between Vim viewports.
    Ctrl-w j moves one viewport down.
    Ctrl-w k moves one viewport up.
    Ctrl-w h moves one viewport to the left.
    Ctrl-w l moves one viewport to the right.

```
