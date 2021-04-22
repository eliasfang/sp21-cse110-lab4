# Part 1a
1. 20
2. 20
3. 20
4. The code returns an error because result becomes undefined after the if block. Let variables only have scope within the block that they are defined.
5. The code returns an error because result cannot be assigned something as a constant variable in line 4. If line 4 is taken away, the code would return 0.
6. The code returns an error because result cannot be assigned something as a constant variable in line 4. If line 4 is taken away, the code would return an error because result would be undefined outside of the if block. Const variables also only have scope within the block that they are defined.

# Part 1b
1. Line 12 will print 3 to the console because i is the index being incremented in the for loop. The for loop terminates when i is greater than or equal to the length of the input array, which is 3 in this case. Thus, i is 3 at line 12.
2. Line 13 will print 150 because before the for loop terminates, discountedPrice will have the 1/2 the value of the last element of the input array, since the discount inputted is 0.5. The last element is 300 and so the discounted price is 0.5 * 300 = 150.
3. Line 14 will print 150 because finalPrice is the value of rounded value of the last discountedPrice divided by 100 divided by 100. So finalPrice = (150 * 100) / 100 = 150.
4. This function will return the final array of discounted prices after the discounts are applied to each of the input array prices. The value returned is [50, 100, 150]. Nothing will be printed to the console since console.log() is not used.
5. Line 12 will print an error because the variable i has been defined using let. Since let only has scope within the block that it is defined, the variable i is undefined outside of the for loop.
6. Line 13 will print an error also because the variable discountedPrice becomes undefined outside of the for loop that it has been defined in. This is because it was defined with let as well.s
7. Line 14 will print 150 without error because the call to print finalPrice is within the same block as where finalPrice is defined. Thus, it will still be defined.
8. The function will successfully return the final array of discounted prices [50, 100, 150] because it was defined and returned in the same block using let.
9. Line 11 will print an error because of the same reason as #5 in that i only exists within the for loop.
10. Line 12 will print 3 successfully because the variable was defined in the same block as a const.
11. The function will still return the updated discounted prices array [50, 100, 150] because even those discounted was defined using const, elements could still be pushed on.
12. Object
    A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
13. Arithmetic
    A. 32
    B. 1
    C. 3
    D. 3null
    E. 4
    F. 0
    G. 3undefined
    H. NaN
14. Comparison
    A. true
    B. false
    C. true
    D. false
    E. false
    F. true
15. === compares the types and values of two operands, whereas == only compares the values of two operands.
16. See part1b-question16.js
17. Passing in the input of [1, 2, 3] and the function doSomething to modifyArray, newArr is first initialized as an empty array. The for loop then iterates through the input array and pushes the value returned by doSomething with the current array element as the parameter. The function, doSomething, just doubles the input and so each of the input array's elements will be doubled in newArr. Thus, the value of newArr returned by modifyArray is [2, 4, 6].
18. See part1b-question18.js
19. The output is:
    1
    4
    3
    2