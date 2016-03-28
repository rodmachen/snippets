# C Syntax != JavaScript

A compendium of C syntax. Focusing on items that differ from JavaScript.

### Misc

Single quotes for single characters; double quotes for strings.
```c
char single_character = 'A';
char string[] = "word";
```

### Output Conversions

Format<br>Specifier | Description
:---: | ---
`%i` | integer

### Escape characters

Character | Meaning
:---: | ---
`\n` | newline
`\0` | null character
`\1` | character with numeric value of 1
`\t` | tab
`\b` | backspace
`\"` | double quote
`\\` | backslash

### Execution Keywords

Operator | Description
:---: | ---
`break` | Exit out of a compound statement
`case` | A branch in a switch-statement
`continue` | Continue to the top of a loop
`default` | Default branch in a switch-statement
`do` | Start a do-while loop
`else` | An else branch of a if-statement
`for` | Start a for-loop
`goto` | Jump to a label
`if` | Starts an if-statement
`return` | Return from a function
`switch` | Start a switch statement
`while` | Start a while-loop

### Type Keywords

Operator | Description
:---: | ---
`char` | Character data type
`double` | A double floating-point data type 
`float` | A floating-point data type
`int` | An integer data type
`long` | A long integer data type
`short` | A short integer data type
`struct` | Combine variables into a single record
`union` | Start a union-statement
`void` | Declare a data type empty

### Data Keywords

Operator | Description
:---: | ---
`auto` | Give a local variable a local lifetime
`const` | Make a variable unmodifiable
`enum` | Define a set of int constants
`extern` | Declare an identifier is declared externally
`register` | Declare a variable be stored in a CPU register
`signed` | A signed modifier for integer data types
`sizeof` | Determine the size of the data
`static` | Preserve variable value after its scope exits
`typedef` | Create a new type
`unsigned` | An unsigned modifier for integer data types
`volatile` | Declare a variable might be modified elsewhere

### Syntax Structures

switch-statement:
```c
switch ({{operand}}) {
    case {{constant}}:
        {{code}};
        break;
    default:
        {{code}};
}
```

### Data Operators
Mainly used with pointers.

Operator | Description
:---: | ---
`sizeof()` | Get the size of
`[]` | Array subscript
`&` | The address of
`*` | The value of
`->` | Structure dereference
`.` | Structure reference

### Bitwise Operators

Operator | Description
:---: | ---
`&` | Bitwise and 
`|` | Bitwise or 
`^` | Bitwise xor
`~` | Bitwise one's complement
`<<` | Bitwise shift left
`>>` | Bitwise shift right
