# Count the total number of lines of code in a folder

In order to count lines of code, first navigate to the correct folder and then run this bash command:

```
$ find . -name '*.js' | xargs wc -l
```

Replace `js` with any file extension, or replace it with `*` to include everything.

Caveat #1: This counts every line, including comments. For me, this was fine because it still shows how much went into creating the app.

Caveat #2: Obviously this wouldn't be very useful with a minimized or otherwise altered code. Aim for the originals.

## Backstory

I recently joined a firm with an existing code base, including a large Angular app. The developers who create it had done a good job separating the code into files and folders (controllers, templates, etc.) When I wanted to put a number to the total lines of code in this app, I had to use the command above. 

### Reference

[Stack Overflow](http://stackoverflow.com/questions/1358540/how-to-count-all-the-lines-of-code-in-a-directory-recursively)
