# Create a symlink

Symlinks (or symbolic links) are often used in conjunction with dotfiles. That's what I'm doing here.

I have a dotfiles repo that houses things like my .vimrc file. I want to keep it in that directory for the sake of version control, but also need it in my home directory so Vim can read it. To accomplish this, I need to make a symlink.

```bash
$ cd ~
$ ln -sf /Users/rmachen/local-code/dotfiles/.vimrc .vimrc
```

To check, I list all files in the home directory.

```bash
$ ls -la
// .vimrc -> /Users/rmachen/local-code/dotfiles/.vimrc
```

There it is. I've got my .vimrc where I need it, but the actual file is elsewhere. It's the best of both worlds. To unlink the file:

```bash
$ unlink .vimrc
```
