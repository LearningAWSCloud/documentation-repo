# Vim Cheat Sheet

## Reference

https://devhints.io/vim

## Exiting

 `:q`  -  Close file without saving

 `:wq` -  Save and close the file

 `:w`  -  Save only


## Clipboard

`x` - Delete character

`dd` - Delete line (cut)

`yy` - Yank line (copy)

`p` - Paste line

`P` - Paste line before

## Find & Replace

`:s%/foo/bar/g` - Replace foo with bar in whole document

## Naviagation

`h` `j` `k` `l` - Arrow keys

`CTRL + u` - Half page up

`CTRL + d`- Half page down

`CTRL + b` - Page up

`CTRL + f` - Page down

## Words

`b` - Previous word

`w` - Next word

`e` - Move to the end if the current word

## Line

`^`/`0` - Move to the beginning of the line

`$` - Move to the end of the line

## Document

`1G` - Move to the first line

`G`  - Move to the end of the file

`:{number}` - Move to {number} line of the file

`{number}j` - Go down to the {number} of lines

`{number}k` - Go up to the {number} of lines


## Window

`zz` - Center the line to middle of the screen

`zt` - Top this line in the screen

`zb` - Bottom this line in the screen

`H` - Move to the top of screen

`M` - Move to the middle of the screen

`L` - Move to bottom of the screen

## Search

`/search` - Search for the word

`n` - Move to the next match pattern

`N` - Move to the previous match pattern

## Operators list

`d` - Delete

    `dd` - Delete current line
    
    `dw` - Delete to next word

    `db` - Delete to the beginning of the word

    `2dd` - Delete 2 lines



`y` - Yank(copy)

`c` - Change(delete and then switch to Insert mode)

`>>` - Right Indent

`<<` - Left Indent

`~` - Swap case and move to the next character

`gU` - Swap the whole line to uppercase

`gu` - Swap the whole line to lowercase

## Miscellanious

`SHIFT + J` - Append the current line with previous line

`r` - Ready to replace the current character

`~` - Toggle the character of the current character and move to next character

## Visual Mode

`v` - Jump into visual character mode

`V` - Jump into visual line mode

`CTRL + v` - Jump into visual block mode

`h` `j` `k` `l` or `Arrow keys` - Use these keys to select the text

    - `U` - Convert the selection into Upper case alphabets

    - `u` - Convert the selection into Lower case alphabets

    - `d` - Delete the selection

    - `c` - Change the selection

    - `y` - Yank the selection

    - `>` - Indent the selection

    - `<` - Dedent the selection

    - `s/foo/bar/g` - To change all the occurences of foo with bar within the selection

## Working with Multiple Tabs

`:e foo.txt` - Opens the existing file foo.txt in a new tab

`:tabnew bar.txt`  - Opens a new empty file called bar.txt

    - `1gt` - Switches to the first tab

    - `2gt` - Switches to the second tab

`vim foo.txt bar.txt` - Opens multiple tabs but in a hidden way

    - `:b1` - Switch to the first tab

    - `:b2` - Switch to the second tab








