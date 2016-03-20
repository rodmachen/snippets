# My Vim Cheatsheet

Not comprehensive.

### Modes
* normal
  * default
  * `<ESC>` from any other mode
* insert
  * for typing code
  * `i` from normal mode
* visual
  * for selecting text (esp. for cutting, pasting, etc.)
  * `v` from normal mode
* command
  * for entering commands
  * `:` from normal mode (followed by the command)

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
--- | ---
`w` | go the beginning of the next word
`e` | go to end of current word
`$` | go to end of line
`0` | go the start of line
