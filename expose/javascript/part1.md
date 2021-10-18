# Expose - Part 1
## var declaration
1. ```values added:  20```
2. ```final result:  20```
## let declaration
3. ```values added:  20```
4. ```ReferenceError: result is not defined```. While ```var``` has no block scope, when we use ```let``` inside ```if```, the variable can only be visible inside ```if```.
## const declaration
5. ```TypeError: Assignment to constant variable```. We cannot reassign the constant (at line 7).
6. ```ReferenceError: result is not defined```. Similar to ```let```, the variable can only be visible inside ```if``` if we use ```const``` inside ```if```.
