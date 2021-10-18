# Expose - Part 2
1. Print ```3```.
2. Print ```150```.
3. Print ```150```.
4. Return ```[50, 100, 150]```. For every term in ```prices```, the final price with discount is deduced and pushed into ```discounted``` in the original order in ```prices```. Also, since we use ```var``` to define ```discounted```, we can access ```discounted``` here.
5. ```ReferenceError: i is not defined```. We use ```let``` to define ```i``` in ```for```, so we cannot use ```i``` outside ```for```.
6. ```ReferenceError: discountedPrice is not defined```. We use ```let``` to define ```discountedPrice``` in ```for```, so we cannot use ```discountedPrice``` outside ```for```.
7. Print ```150```. We define ```finalPrice``` with ```let``` outside ```for```, so we can use ```finalPrice``` here.
8. Return ```[50, 100, 150]```. For every term in ```prices```, the final price with discount is deduced and pushed into ```discounted``` in the original order in ```prices```. Also, since we use ```let``` to define ```discounted``` outside ```for```, we can access ```discounted``` here.
9. ```ReferenceError: i is not defined```. We use ```let``` to define ```i``` in ```for```, so we cannot use ```i``` outside ```for```.
10. Print ```3```. ```length``` is defined with ```const``` outside ```for```, and it is not reassigned afterwards, so we can access it here.
11. Return ```[50, 100, 150]```. For every term in ```prices```, the discounted price is deduced and pushed into ```discounted``` in the original order in ```prices```. Also, since we use ```const``` to define ```discounted``` outside ```for```, we can access ```discounted``` here.
12.
- A. ```student.name```
- B. ```student['Grad Year']```
- C. ```student.greeting();```
- D. ```student['Favorite Teacher'].name```
- E. ```student.courseLoad[0]```
13.
- A. ```32``` since integers map to their exact string representation
- B. ```1``` since strings map to their exact integer representation (in subtraction)
- C. ```3``` since ```null``` maps to ```0```
- D. ```3null``` since ```null``` maps to the corresponding string ```'null'```
- E. ```4``` since ```true``` maps to ```1```
- F. ```0``` since ```false``` & ```null``` both map to ```0```
- G. ```3undefined``` since ```undefined``` maps to the corresponding string ```'undefined'```
- H. ```NaN``` since ```undefined``` does not map to certain integer
14.
- A. ```true``` since strings map to their exact integer representation
- B. ```false``` since ```'2'``` is bigger than ```'1'``` in string comparison
- C. ```true``` since strings map to their exact integer representation
- D. ```false``` since the types are different
- E. ```false``` since ```true``` maps to ```1```
- F. ```true``` since ```Boolean(2)``` is ```true```
15. ```==``` allows type conversion while ```===``` doesn't.
16. See **part2-question16.js**.
17. Return ```[2, 4, 6]```. For every term in ```[1, 2, 3]```, the modified number by the function ```doSomething()```, as ```callback``` in ```modifyArray()```, is deduced and pushed into ```newArr``` in the original order in ```[1, 2, 3]```. Since ```doSomething()``` lets the number multiplied by 2, every term in ```[1, 2, 3]``` is modified by being multiplied by 2.
18. See **part2-question18.js**.
19. 
```
1
4
3
2
```
