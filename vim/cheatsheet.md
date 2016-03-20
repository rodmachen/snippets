# Vim Cheatsheet

Subjective. Incomplete. 

### Modes

Name | Purpose | Command
--- | --- | ---
normal | default | `<ESC>` from any other mode
insert | typing code | `i` from normal mode
visual | selecting text <br> (esp. for cutting, pasting, etc.) | `v` from normal mode
command | entering commands | `:` from normal mode<br>(followed by the command)

### File management

Open file
```bash
$ vim <filename>
```

Close and exit
```vim
ZZ
```

### Movement

Enter | Result
:---: | ---
`w` | go the beginning of the next word
`e` | go to end of current word
`$` | go to end of line
`0` | go the start of line
`h` or ← | left one character
`j` or ↓ | down one line
`k` or ↑ | up one line
`l` or → | right one character

Preface any movement with a number to increase movement.

Enter | Result
:---: | ---
`1w` | same functionality as `w`
`2e` | go to end of next word
`3$` | go to end of third line
`4` ← | left 4 characters
`5` ↓ | down 5 lines
`6` ↑ | up 6 lines
`7` → | right 7 characters

### Deletion

Preface any movement with `d` to delete starting at current location.

Enter | Result
:---: | ---
`dw` | delete through beginning of next word
`d2e` | delete through end of next word
`d3$` | delete through end of third line
