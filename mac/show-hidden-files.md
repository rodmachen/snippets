# Show hidden files in the Finder

The Mac OS gets pretty clever with its file types, and there's a whole world of hidden files lurking just out of view. Seeing them in the Terminal is easy, but to make them appear in the Finder takes a little more work. Start by running this command:

```
$ defaults write com.apple.finder AppleShowAllFiles TRUE
```

(When searching the solution to this problem, I found various versions of this command, with `write` sometimes replaced by `read` and `TRUE` with `YES`. This is the one that worked for me.)

The final step is to restart the Finder. While that can be done via Force Quit, it's easy to accomplish in the Terminal:

```
$ killall Finder
```

Caveat: There's an ugly little file called DS_store that does nothing but store the way the contents of a folder are shown in the finder. Navigating to any folder will create one, and this can be a mess for git operations. The solution is simply to add it to `.gitignore`.

## Backstory

The biggest reason I always set up my environment this way is so I can use the finder to copy all of the contents of a folder, including things like `.git`.

### Reference

[How to Hide Files and View Hidden Files on Mac OS X](http://www.howtogeek.com/211496/how-to-hide-files-and-view-hidden-files-on-mac-os-x/)
