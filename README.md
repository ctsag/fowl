<div style="text-align:center"><img src="./img/logo_transparent.png" /></div>

# The Fowl Programming Language

Fowl is a programming language that aims to restrict the use of as many
code constructs as possible that are prone to leading into code smells.

Fowl is heavily inspired by the work done on the field of refactoring by
Martin Fowler, from whom the language's name is inspired.

## Manifesto

1. Comments don't exist

2. Switch statements don't exist

3. Ternary operator doesn't exist

4. Single statement per line


5. No global variables

6. Unused variables/functions are not allowed

7. Variable/function names 

    - are at least 3 letters long
    - cannot start with 'my' or 'test'
    - cannot end with a number or 'new'
    - cannot contain '-' or '_'

8. Function parameters are required to be documented

9. The cyclomatic complexity of a function does not exceed 10

10. All errors must be handled