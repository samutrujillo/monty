### About the project
The goal of this project is to create an interpreter for Monty ByteCodes files.

### Resources
...

### Usage C scripts
```sh
gcc -Wall -Werror -Wextra -pedantic *.c -o monty
./monty <file>
```

</br>

## Commands

| Opcode | Description |
|---------------- | -----------|
|push   | Pushes an element to stack |
|pall   | Prints all elements in stack |
|pint   | Prints first stack node|
|pop    | Removes removes last stack node |
|swap   | Inverts stack nodes positions |
|add    | Adds top two stack elements|
|nop    | Ignores command |
|sub    | Subtracts top two stack elements |
|div    | Divides top two stack elements |
|mul | Multiplies top two stack elements|
|mod    | Computes division remainder from top two stack elements|
|#      | Comments instruction|
|pchar  | Prints first stack element in ascii value |
|pstr   | Prints all stack elements in ascii value |
|rotl   | Sends first stack element to last position |
|rotr   | Send last stack element to first position |
|stack  | Sets stack format to LIFO (Last In First Out) |
|queue  | Sets stack format to FIFO (First In, First Out) |

## Author
Samuel Trujillo