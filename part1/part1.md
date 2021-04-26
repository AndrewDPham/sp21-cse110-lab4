1. 20
2. 20
3. 20
4. Error. This is because result is declared with the let keyword in another block.
5. Error. This is because result is a const and it can't be changed to (sum1 + sum2).
6. Error. This line is never reached. There is also an attempt to reassign the result variable which is not possible.

1. 3. This is because i will increment until it meets the condition and increment one more time after in order to exit the for loop. The condition is i < prices.length so i == 2 and it will increment one more time so it is 3.
2. 150. This is because discountedPrice is equal to ```prices[2] * (1-.05)``` which is 150 since ```prices[2]``` is 300. 
3. 140. 
4. [50, 100, 150]
5. Error. i is not defined here since it is only defined in the for block.
6. Error. discountedPrice is not defined here since it is only defined in the for block.
7. 150
8. [50, 100, 150] EXPLAIN. and num 4 and 11.
9. Error. i is not defined here since it is only defined in the for block.
10. 3
11. [50, 100, 150]. This is because

12. 
a. student.name
b. student["Grad Year"]
c. student
d. student["Favorite Teacher"][1]
e. student.courseLoad[1]

13. 
a. 32. 2 gets converted into a string and gets concatenated to 3 so it becomes 32.
b. 1. 3 gets converted into a number and then is subracted by 2 to make 1.
c. 3. This is because null is converted to 0 and 3 + 0 is 3.
d. 3null. This is because null gets converted to a string and is concatenated to 3 making it 3null.
e. 4. true gets converted to 1 and is added to 3 making it 4.
f. 0. false and null is converted to 0 and 0 + 0 is 0.
g. 3undefined. undefined is converted to a string and is concatenated to 3 making it 3undefined.
h. Nan

14. 
a. true. "2" is converted to 1 and 
b. false. "2" is compared to "12" lexigraphically and it is false since "12" is greater lexigraphically.
c. true. They are the same value after "2" is converted to a number.
d. false. This is a strict equality check and the types are not the same.
e. false. true is converted to 1 but it is not equal to 2.
f. true. Boolean(2) is converted to true and true is strictly equal to true.

15. == is a normal equality while === is a strict equality checking both equality and type. 

16. Done[./part1b-question16.js]

17. [2, 4, 6]. We create a new array (newArr) and this is 

18. Done[./part1b-question18.js]

19. 1
    4
    3
    2
