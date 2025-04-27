1. it will print 3. That is because in the for loop, we are using a var i to iterate through the size of prices which is 3. 
2. It will print 150. On the last iteration of the loop, we set var discountedPrice to 150 which is 300*0.5. So when we print it outside the for loop, the var hasn't changed since the last iteration. 
3. This will also print 150 due to similar reasoning as number 2. The final price in the last iteration of the loop is not changed, and since its a var we can use it outside of the for loop scope. 
4. it will return the array [50, 100, 150]. Even though we use var, meaning that finalPrice, discountedPrice and i are accessible outside their scope, it does not cause any errors and the function behaves normally. 
5. this will cause an error because we are trying to access the variable i outside of its scope
6. we will get an error because we are trying to access the variable discountedPrice outside of its scope of the for loop block 
7. it will log the last final price, which is 150. This is because finalPrice was declared in the same block as the log statement, so we are able to access it. 
8. This will return the array [50, 100, 150] as expected, since we are still accessing variables at the correct scope
9. it will cause an error because we are trying to access the variable i outside of its scope which is the for loop
10. the function will print out 3, because we are correctly accessing the variable length in the same block/scope
11. the function will return [50, 100, 150] as expected. Even though the discount array is const, we can still modify the array just not the reference to the array. and even though we use const discountedPrice in the loop, every loop is a new block so it is a fresh variable every time. 
12. a. student.name
    b. student['Grad Year']
    c. student.greeting()
    d. student['Favorite Teacher'].name
    e. student.courseLoad[0]
13. a. '32' - ints map to string representation
    b. 1 - string maps to int representation 
    c. 3 - null is 0
    d. '3null' - null string is 'null'
    e. 4 - true is 1
    f. 0 - false and null are zero in int
    g. '3undefined' - undefined in string
    h. NaN - convert both to ints, but undefined is NaN
14. a. true - int value of 2 greater than 1
    b. false - lexicographically not true 
    c. true - int of '2' is 2
    d. false - strict equality with no type conversion
    e. false - true is 1 in ints
    f. true - Boolean(2) is true
15. == is a loose equality compare, we try to convert to same type first. === is strict equality, we compare values without converting. 
16. see part2-question16.js
17. [2,4,6]. each element of the array gets passed to the callback function which is doSomething. doSomething simply doubles the number. 
18. see part2-question18.js
19. 1 4 3 2