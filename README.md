# RPN Calculator by Akbar BadShah

It's a full-fledged rpn calculator I made to practice my pythonic skills. Works fine to the best of my knowledge, but you're still welcome to share your thoughts, add features, report and correct bugs.

# New Features!
- `+` : Take 2 numbers from the stack, add them and put the result in the stack
- `-` : Take 2 numbers from the stack, substracte them and put the result in the stack
- `*` : Take 2 numbers from the stack, mul them and put the result in the stack
- `/` : Take 2 numbers from the stack, divise them and put the result in the stack
- `cla` : Clear both stack and variable
- `clr` : Empty the stack
- `clv` : Clear both stack and variable
- `!` : None
- `!=` : Return True if last two numbers in stack are equal, False otherwise
- `%` : Take 2 integers from the stack, divide them and put the remainder in the stack
- `++` : Increment an integer
- `--` : Decrement an integer
- `&` : Take 2 numbers from the stack, apply a bitwise "and" and put the result in the stack
- `|` : Take 2 numbers from the stack, apply a bitwise "or" and put the result in the stack
- `^` : Take 2 numbers from the stack, apply a bitwise "xor" and put the result in the stack
- `~` : Take 2 numbers from the stack, apply a bitwise "xor" and put the result in the stack
- `<<` : Take 2 numbers from the stack, apply a left shift and put the result in the stack
- `>>` : Take 2 numbers from the stack, apply a right shift and put the result in the stack
- `&&` : Perform boollean AND operation on two values and output the result (not added to the stack)
- `||` : Perform boollean OR operation on two values and output the result (not added to the stack)
- `^^` : Perform boolean XOR operation on two values and output the result (not added to the stack)
- `<` : Smaller than operation on two values and output the result (not added to the stack)
- `<=` : Smaller than or equal to operation on two values and output the result (not added to the stack)
- `==` : Equal to operation on two values and output the result (not added to the stack)
- `>` : Greater than operation on two values and output the result (not added to the stack)
- `>=` : Greater than operation on two values and output the result (not added to the stack)
- `acos` : Take arc cosine on a value and output the result (also added to the stack)
- `asin` : Take arc sine on a value and output the result (also added to the stack)
- `atan` : Take arc tangent on a value and output the result (also added to the stack)
- `cos` : Take cosine on a value and output the result (also added to the stack)
- `cosh` : Take arc hyperbolic cosine on a value and output the result (also added to the stack)
- `sin` : Take sine on a value and output the result (also added to the stack)
- `sinh` : Take hyperbolic sine on a value and output the result (also added to the stack)
- `tanh` : Take hyperbolic tangent on a value and output the result (also added to the stack)
- `ceil` : Take ceil of an integer and output the result (also added to the stack)
- `floor` : Take floor of an integer and output the result (also added to the stack)
- `round` : Take round of an integer and output the result (also added to the stack)
- `ip` : Separates int from floating part of a decimal number and output the result (also added to the stack)
- `fp` : separates floating part of a decimal number and output the result (also added to the stack)
- `abs` : Take ceil of an integer and output the result (also added to the stack)
- `max` : Take maximum value of the stack and output the result (also removed from the stack)
- `min` : Take minimum value of the stack and output the result (also removed from the stack)
- `hex` : Change display mode to hex
- `bin` : Change display mode to binary
- `dec` : Change display mode to decimal
- `e` : None
- `pi` : None
- `rand` : None
- `exp` : Apply e**x to the last number of the stack
- `fact` : Push factorial of the last number to the stack
- `sqrt` : Push factorial of the last number to the stack
- `ln` : Apply log10 to the last number of the stack
- `log` : Apply log10 to the last number of the stack
- `pow` : Take 2 numbers from the stack, apply power and put the result in the stack
- `pick` : Pick the nth item form stack
- `repeat` : Repeat an operation n times
- `drop` : Drop the top most item from the stack
- `dropn` : Drop the n top most items from the stack
- `dup` : Duplicates the top item from the stack
- `dupn` : Duplicates n top items of thew stack
- `roll` : Roll the stack upwards by n
- `rolld` : Roll the stack downwards by n
- `stack` : Toggles stack display from horizontal to vertical
- `swap` : Swap the top 2 stack items
- `x=` : Assigns a variable, e.g. '1024 x='
- `help` : Print help; Same as pol --list
- `exit` : Quit the program

### Available Modes
- For one time result of a single line statement, do:
> rpn 3 2 + #(should exit outputting 5)
- To solve statements from a file before entering shell, do:    
> rpn --file #path
- To simply enter the shell, do:
> rpn

### Installation

>pip install advanced_rpn_calculator

### Todos

 - Write MORE Tests or just test if everything works fine.

License
----

MIT


**Free Software, Hell Yeah!**
