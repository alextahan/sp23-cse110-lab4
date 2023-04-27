1. Since `i` is a var and is output after the for loop, `prices.length` is outputted, or **3**.
2. Since `discountedPrice` has no block scope, the discounted price of the last index of the array will be outputted, which is **150**.
3. Since `finalPrice` is a `var` and has no block scope, line 14 will output the final price of the third item, which is **150**.
4. This function returns the array `discounted`, which contains `[50,100,150]`
5. Since `i` is defined within the for loop, it cannot be accessed outside of it and the code returns an **error**
6. Since `discountedPrice` is defined within the for loop, it cannot be accessed outside of it and the code returns an **error**
7. Since `finalPrice` is defined outside the for loop, line 14 will output the final price of the third item, which is **150**.
8. This function returns the array `discounted`, which contains `[50,100,150]`
9. Since `i` is defined within the for loop, it cannot be accessed outside of it and the code returns an **error**
10. Since length is defined outside the for loop, the code will output **3**
11. Since `discounted` points to the location of an array, pushing a value to the array does not reassign the variable and is still possible, even though `discounted` is a `const`. Therefore, `[50,100,150]` is returned.
12. 
    1.  `student.name`
    2.  `student['Grad Year']`
    3.  `student.greeting()`
    4.  `student['Favorite Teacher'].name`
    5.  `student.courseLoad[0]`
13. 
    1.  '32'; The integer 2 maps to its string representation and concatenates with '3'
    2.  1; Since `-` is a math operation, the string '3' converts to a number 
    3.  3; `null` maps to a value of 0.
    4.  '3null'; `null` converts to the string 'null'.
    5.  4; `true` maps to a value of 1.
    6.  0; both `false` and `null` map to 0, and are added together.
    7.  '3undefined'; `undefined` converts to 'undefined' and is concatenated with '3'
    8.  NaN; since `-` is a math operator, '3' converts to 3 and undefined converts to NaN, producing NaN
14. 
    1.  true; the string '2' becomes a number and 2>1
    2.  false; when comparing strings, it's compared in lexicographical order, character by character. For the first character of each string, '2'>'1'.
    3.  true; the string '2' becomes a number
    4.  false; 2 and '2' are different types, so `===` returns false
    5.  false; `true` maps to 1, which is not equal to 2
    6.  true; `Boolean(2)` evaluates to `true`, and which is equal value and type to `true`
15. Both `==` and `===` compare the two values to determine if they are equal, but `===` does not allow a type conversion, meaning that the values must be the same type for this to be true.
16. *see `part2-question16.js`*
17. The function iterates through the passed `array` in a for loop. At each index, it calls the passed `callback` function with the value at that index. It stores the returned value in a new array, which is returned at the end. For `modifyArray([1,2,3], doSomething)`, since `doSomething` returns double whatever value is passed to it, each value in `[1,2,3]` will be doubled, returning `[2,4,6]`.
18. *see `part2-question18.js`
19. 
```
//Output:
1
3
4
2
```


