# Vim Cheatsheet

Subjective. Incomplete. 

### Modes

Name | Purpose | Command
--- | --- | ---
normal | default | `<ESC>` from any other mode
insert | typing code | `i` from normal mode
visual | selecting text <br> (esp. for cutting, pasting, etc.) | `v` from normal mode
command | entering commands | `:` from normal mode (followed by the command)

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
