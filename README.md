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
