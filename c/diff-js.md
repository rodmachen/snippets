# C Syntax != JavaScript

A compendium of C syntax. Focusing on items that differ from JavaScript.

### Keywords

Operator | Description
:---: | ---
`auto` | Give a local variable a local lifetime
`break` | Exit out of a compound statement
`case` | A branch in a switch-statement
`char` | Character data type
`const` | Make a variable unmodifiable
`continue` | Continue to the top of a loop
`default` | Default branch in a switch-statement
`do` | Start a do-while loop
`double` | A double floating-point data type 
`else` | An else branch of a if-statement
`enum` | Define a set of int constants
`extern` | Declare an identifier is declared externally
`float` | A floating-point data type
`for` | Start a for-loop
`goto` | Jump to a label
`if` | Starts an if-statement
`int` | An integer data type
`long` | A long integer data type
`register` | Declare a variable be stored in a CPU register
`return` | Return from a function
`short` | A short integer data type
`signed` | A signed modifier for integer data types
`sizeof` | Determine the size of the data
`static` | Preserve variable value after its scope exits
`struct` | Combine variables into a single record
`switch` | Start a switch statement
`typedef` | Create a new type
`union` | Start a union-statement
`unsigned` | An unsigned modifier for integer data types
`void` | Declare a data type empty
`volatile` | Declare a variable might be modified elsewhere
`while` | Start a while-loop

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
