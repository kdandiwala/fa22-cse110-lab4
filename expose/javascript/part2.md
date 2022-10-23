1. `3` will be printed because the for loop runs 3 times (the length of prices) and sets the global variable `i` to be 3. 
2. `150` will be printed since its the last value `discountedPrice` takes in the for loop (300 * 0.5) 
3. `150` will be printed since its the last value `finalPrice` takes in the for loop [(150 * 100) / 100]
4. The function will return an array called `discounted` that discounts each price in the array based on the discount parameter. In this case, each price is half off. 
5. The code causes an error because `i` is not defined outside of the for loop as it uses the keyword `let`.
6. The code causes an error because `discountedPrice` is not defined outside of the for loop as it uses the keyword `let`.
7. `150` will be printed since its the last value `finalPrice` takes in the for loop [(150 * 100) / 100]. Although `finalPrice` is defined using `let`, its defined in the same scope as the `console.log()` statement so it doesn't throw an error. 
8. The function will return an array called `discounted` that discounts each price in the array based on the discount parameter. Even though every variable is defined using `let` they are all enclosed and used in the scope of the function so no errors are thrown.
9.  This causes an error because `i` is defined in the scope of the for loop so it cannot be accessed from the function body in the `console.log()` statement. 
10. `3` will be printed which is the length of the `prices` array. Since `length` is defined in the same scope as the `console.log()` statement, no errors are thrown. 
11. The function will return an array called `discounted` that discounts each price in the array based on the discount parameter. Even though the `discounted` array is defined using the `const` keyword, the `discounted` can still be added to, just not reassigned to another array. 
12. Notations
    1.  student.name
    2.  student["Grad Year"]
    3.  student.greeting();
    4.  student["Favorite Teacher"].name
    5.  student.courseLoad[0]
13. Arithmetic
    1.  '32' because 2 is converted into a string and appended to '3'
    2.  1 because 3 is converted into an integer and subtracted by 2 
    3.  3 because null is converted to the integer 0 and added to 3
    4.  '3null' because null is converted into a string and appended to '3'
    5.  4 because true is converted into the integer 1 and added to 3
    6.  0 because false and null are converted into the integer 0 and then added together. 
    7.  '3undefined' because undefined is converted into a string and appended to '3'
    8.  NaN (not a number) because undefined cannot be converted into an integer and used for subtraction.  
14. Comparison
    1.  Returns true because '2' gets converted into an integer and then is compared to 1. 
    2.  Returns false because '2' is alphabetically greater than '12'.
    3.  Returns true because '2' is converted to the integer 2 and then checked for equality with 2.
    4.  Returns false because '2' and 2 are different types. 
    5.  Returns false because true is converted into the integer 1 which is not equal to 2.
    6.  Returns true because Boolean(2) evaluates to true which is the same type as true.
15. The `==` operator does a type conversion before checking for equality where as the `===` operator checks the values and data types of the operands during the comparison. 
16. Check part2-question16.js
17. `modifyArray([1,2,3], doSomething)` will return `[2, 4, 6]`. When `doSomething()` is set as the callback in `modifyArray()`, each element in `array` is passed as a parameter into `doSomething()` which returns it doubled, later pushed into `newArr`. 
18. Check part2-question18.js
19. The code prints `1 4 3 2` since the individual log statements are evaluated first with the `console.log(3)` inside the zero second delay `setTimeout` function evaluated right after. `2` is printed a second after the other numbers.  