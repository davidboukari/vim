# vim

## Replacce \n => \r
```
: 1,$ s/}/}\r/g
```

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

## To display the byte position you can use the following command
```
:echo line2byte(line("."))+col(".")-1
```

## go to offset
```
:goto 2356
```

## Tab => 2 spaces
```
filetype plugin indent on
" On pressing tab, insert 2 spaces
set expandtab
" show existing tab with 2 spaces width
set tabstop=2
set softtabstop=2
" when indenting with '>', use 2 spaces width
set shiftwidth=2
```

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
