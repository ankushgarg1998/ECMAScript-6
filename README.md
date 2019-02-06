# ES6 Summary

### VARIABLES
- **var**
  - function scope. (leaks out of an If{} block).
  - allows updation and redeclare.
  - ~~Temporal Dead Zone~~ variables are accessible even before they are created but their value is inaccessible (undefined)(no error).
- **let**
  - block scope. (doesn't leaks out of a block).
  - allows updation but not redeclaration.
- **const**
  - block scope.
  - cannot be updated.
  - if const is used to decalre an object, its attributes may change.

#### Approach
  - Use **const** by default.
  - Use **let** only if the value of the variable needs to be changed.
  - Never use **var**

### FUNCTIONS
- **Arrow Functions**
  - Syntax
  - Implicit return
  - *'this' is not passed. 'this' is inherited from parent.*
- Default Function Arguments

### STRINGS
- **Template Strings**
  - Syntax
  - can be multi-line without using '\'.
  - can be nested.
    - can use loops and if(ternerary) statements.
  - Tagged Template Literals (Actual Working)
    - Possibly applicable in preventing XSS(cross-site-scripting)
- Additional Functions
  - String
    - .startsWith()
    - .endsWith()
    - .includes()
    - .repeat()

### DESTRUCTURING
- **Objects**
  - not order sensitive
  - Variable Renaming
  - Default Arguments
- **Arrays**
  - order sensitive
  - Swapping
  - rest operator

### FOR OF **LOOP**
  - All types of loops
  - The FOR-OF loop (usable on all iterables)
    -  Objects - For-in

```javascript
var s = "yo"
console.log(s);
```