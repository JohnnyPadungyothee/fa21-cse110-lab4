1. At line 12, we will print out '3' because i was declared using var, so it has a function scope, and i is incremented to 3 before it exits the loop.
2. At line 13, we will print out '150' because discountedPrice was declared using var, so it has a function scope, and the last assignment to discountedPrice was 300 * (0.5), which is 150.
3. At line 14, we will print out '150' because finalPrice was declared using var, so it has a function scope, and the last assignment to finalPrice was Math.round(150 * 100) / 100, which is 150.
4. This function will return the array [50,100,150] because the loop takes each number in the prices array and multiplies it by 0.5 before rounding it and pushing onto the discounted array.
5. Error. Since i was declared using let, once we exit from the for loop, i is out of scope and therefore a call to it at line 12 returns a variable undefined error.
6. Error. Since discountedPrice was delcared using let, once we exit from the for loop, discountedPrice is out of scope and therefore a call to it at line 13 returns a variable undefined error.
7. At line 14, we will print out '150' because the last assignment for finalPrice was Math.round(150 * 100) / 100, which is 150.
8. This function will return the array [50,100,150] because the loop takes each number in the prices array and multiplies it by 0.5 before rounding it and pushing onto the discounted array.
9. Error. Since i was declared using let, once we exit from the for loop, i is out of scope and therefore a call to it at line 11 returns a variable undefined error.
10. At line 12, we will print out '3' because length was assigned to prices.length and prices has 3 elements.
11. This function will return the array [50,100,150] because the loop takes each number in the prices array and multiplies it by 0.5 before pushing onto the discounted array.
12. A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher']['name']
    E. student['courseLoad'][0]
13. A. "32" The integer 2 mapped to its string representation and then concatenated with '3'
    B. 1 The string '3' is mapped to its integer representation and 3 - 2 = 1
    C. 3 Null is mapped to the integer value 0 and 3 + 0 = 3
    D. '3null' Null is mapped to its string representation and then concatenated with '3'
    E. 4 true is mapped to its integer representation of 1 and 1 + 3 = 4
    F. 0 false and null both map to an integer representation of 0 so 0 + 0 = 0
    G. "3undefined" undefined is mapped to its string representation and then concatenated with '3'
    H. NaN undefined is mapped to NaN and '3' is mapped to its integer representation so 3 - NaN = NaN
14. A. true '2' is mapped to its integer representation so 2 > 1 is true
    B. false Since both are strings, this does string comparison and char '2' is greater than char '1' (1 is the first character from '12') so this is false
    C. true '2' is mapped to its integere representation so 2 == 2 is true
    D. false === is a strict equality operator so different types immediately returns false
    E. false the integer representation of true is 1 so 1 == 2 is false
    F. true Since 2 is not one of the intuitively "empty" values, it converts to true and a true === true is true
15. The normal equality operator ==, converts operands of different types to numbers so 0 == false would be true. The strict equality operator === does not type convert so operands of different types are immediately false.
16. in part2-question16.js
17. [2,4,6]. When we call modifyArray([1,2,3], doSomething), we are passing a function as a parameter. So once we enter the loop in modifyArray, we call callBack, which is the function doSomething, and it takes the element in the array and doubles it then pushes it into the newArr. Therefore, at the end of the loop, the newArr contains the elements from the array doubled.
18. in part2-question18.js
19. 1
    4
    3
    2
    