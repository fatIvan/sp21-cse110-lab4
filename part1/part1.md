Part 1a
1. values added:  20
2. final result:  20
3. values added:  20
4. Error, because the console.log('final result: ', result); is outside of the if-block which the variable "result" is declared in.
5. Error, because on line 9, it is trying reassign it to another value which is prevented by the const keyword.
6. Error, because the "result" is only declared in the if-block, so it is not defined when trying to print the "result" outside of the if-block.

Part1b
1. It prints out 3, because the iterator i is a var, which means that it has a function scope and can be console logged after the for loop. Since there are 3 prices, the iterator i will increment until 3 and finds out that it will no longer go into the for loop, therefore console.log(i) will print out 3.
2. It prints out 150, because the discountedPrice is of type var, which means that it can be accessed outside of the for loop inside the function scope. The last iteration of the for loop took the last price in the prices array and do the calculation which is discountedPrice = 300*(1-0.5) which results in 150.
3. It prints out 150, because the finalPrice is of type var, which means that it can be accessed in the function scope. The last iteration of the for loop kept the value of finalPrice to be finalPrice = Math.round(discountedPrice * 100) / 100 = 150 which results in 150.
4. It will return [ 50, 100, 150 ], because the returned value is discounted, which is an array. Inside the for loop, there are three values, 50, 100, 150, pushed into it in this order, therefore, the returned value should be [ 50, 100, 150 ].
5. Error, because the iterator i is declared in the scope of the for-loop, the console.log(i) is outside of the for loop, therefore there is an error on line 12.
6. Error, because the variable discountedPrice is declared using the "let" keyword which can be only used in the for loop block scope.
7. It will not cause an error. If we assume the function is called like this: discountPrices([100, 200, 300], 0.5), then it will print out 150 on line 14, because the finalPrice variable is declared using the "let" keyword, which the variable can be only used in the block scope. In the case, the block is the same as the function because it is declared within the function without any other block scope. 
8. It will return  [ 50, 100, 150 ] because the discounted variable is declared using the "let" keyword within its block scope as an array, in this case, its scope is the function. Then after 3 iterations of the for loop, 50, 100, 150 are pushed into the array and then returned, therefore the function returns [ 50, 100, 150 ].
9. Error, because the iterator i was declared using the "let" keyword, which is has a block scope, in which the variable can be only used in the for loop. The console.log is outside of the for loop, therefore there is an error.
10. Line 12 prints out 3 because the const length is declared in the block scope which is the same as the function discountPrices, therefore line 12 prints out 3.
11. The function will return [ 50, 100, 150 ] because the discounted variable is an array and there are 3 values 50, 100, 150, pushed into it. There is not any error with the code and therefore it will return [ 50, 100, 150 ].
12. A. student.name
    B. student["Grad Year"]
    C. student.greeting()
    D. student["Favorite Teacher"].name
    E. student.courseLoad[0]
13. For number 13, if I copy paste the ' ', it says that it is a syntax error, so I replaced them with '' on my keyboard and the results are below.
    A. '32', intergers map to their exact string representation and then '2' concatenates after '3'.
    B. 1, string is converted to number, and do the numeric subtraction.
    C. 3, null converts to 0 and do the numeric addition.
    D. '3null', null converts to string 'null' and concatenates after '3'.
    E. 4, true is converted to 1 and do numeric addition and get 4.
    F. 0, false and null are both converted to 0 and then do addition, which results in 0.
    G. '3undefined', undefined is converted to string and do the concatenation.
    H. NaN, '3' and undefined are converted to 3 and NaN and do the subtraction, the result is NaN.
14. For number 14, if I copy paste the ' ', it says that it is a syntax error, so I replaced them with '' on my keyboard and the results are below.
    A. true, string '2' becomes a number 2
    B. false, string '2' has a greater first character value than string '12'
    C. true, string '2' becomes a number 2
    D. false, '2' and 2 has different type.
    E. false, true is converted to 1 and 1 does not equal 2, so false.
    F. true, Boolean(2) is true and they are equal and of the same type as well, therefore true.
15. A regular equality check == will convert the operands to numbers first if they are of different types and then do the comparison, however, a strict equality operator === checks the equality without type conversion.
16. In part1b-question16.js
17. It will be [ 2, 4, 6 ], because in the beginning, the [ 1, 2, 3 ] and doSomething functions are passed in as parameters, then each element in the array are passed into the doSomething function and then the results are pushed into the newArr array, which are [ 2, 4, 6 ].
18. In part1b-question18.js
19. The output is below
    1
    4
    3
    2
    because the function first logs 1 then is still busy with logging 4, so it then logs 4 and because logging 3 has a shorter wait time, then it logs 3 and at last it logs 2.

