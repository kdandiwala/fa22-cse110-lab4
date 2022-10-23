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