## Part 1a
1. 20
2. 20
3. 20
4. Error. This is because result is declared with the let keyword in another block.
5. Error. This is because result is a const and it can't be changed to (sum1 + sum2).
6. Error. This line is never reached. There is also an attempt to reassign the result variable which is not possible.

## Part 1b
1. 3, This is because i will increment until it meets the condition and increment one more time after in order to exit the for loop. The condition is i < prices.length so i == 2 and it will increment one more time so it is 3.
2. 150, This is because discountedPrice is equal to ```prices[2] * (1-.05)``` which is 150 since ```prices[2]``` is 300. 
3. 150, This is because in the last iteration of the loop, discountedPrice will be 150. In the last iteration of the loop, performing Math.round((150*100)/100) gives us 150 as the answer.
4. [50, 100, 150]. This is because the loop essentially loops through the prices array and reduces by the discounted price. Since the discounted price is .5, it is taking 50% of the original values of prices, making it [50, 10, 150].
5. Error. i is not defined here since it is only defined in the for block.
6. Error. discountedPrice is not defined here since it is only defined in the for block.
7. 150, This is because finalPrice is in the scope of the function and it is not declared in the for block.
8. [50, 100, 150]. This is because discounted is declared outside of the for block and it is also scoped within the function.
9. Error. i is not defined here since it is only defined in the for block.
10. 3, this is because length is a const varible but it is not being changed or reassigned anywhere else in the function. 
11. [50, 100, 150]. This is because discounted is iniatilize as a const and so we are pushing to the array but not reassigning the variable.

12. 
A) student.name
B) student["Grad Year"]
C) student.greeting()
D) student["Favorite Teacher"].name
E) student.courseLoad[0]

13. 
A) "32". 2 gets converted into a string and gets concatenated to 3 so it becomes "32".
B) 1. 3 gets converted into a number and then is subracted by 2 to make 1.
C) 3. This is because null is converted to 0 and 3 + 0 is 3.
D) "3null". This is because null gets converted to a string and is concatenated to 3 making it 3null.
E) 4. true gets converted to 1 and is added to 3 making it 4.
F) 0. false and null is converted to 0 and 0 + 0 is 0.
G) "3undefined". undefined is converted to a string and is concatenated to 3 making it 3undefined.
H) "NaN". This is because undefined is converted to NaN and subtracting with NaN results in a NaN.

14. 
A) true. "2" is converted to 1 and 
B) false. "2" is compared to "12" lexigraphically and it is false since "12" is greater lexigraphically.
C) true. They are the same value after "2" is converted to a number.
D) false. This is a strict equality check and the types are not the same.
E) false. true is converted to 1 but it is not equal to 2.
F) true. Boolean(2) is converted to true and true is strictly equal to true.

15. == is a normal equality that does type conversion before comparing while === is a strict equality, checking both equality and type (does not perform type conversion before). 

16. [Done](./part1b-question16.js)

17. [2, 4, 6]. We create a new array (newArr) and this is 

18. [Done](./part1b-question18.js)

19. 1
    4
    3
    2
