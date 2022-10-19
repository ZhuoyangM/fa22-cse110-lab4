1. It will print prices.length-1, since i is declared using keyword var, which means i is visible through the entire function. The for loop processes every price in array prices so i is set to the index of last price in prices.
2. It will print the discounted price for the last price in prices, as discountedPrice has type var and can be seen outside the for loop.
3. It will print the final price for the last price in prices, since finakPrice is declared at the start of the function and is visible for the entire function.
4. The function will return an array containing final prices for each price in the array prices. This function has a for loop where during each iteration it computes the final price of each price in the input array prices and push this final price to the result array discounted.
5. This will result in an error. Notice that varible i is declared using keyword let and inside the for loop, so it only has the for loop scope. Attempting to read it after for loop will give us an error.
6. It will return an error, since discountedError is declared and only valid in the for loop.
7. It wil print the final price for the last price in array prices, since finalPrice is declared at the start of the function and is accessible everywhere in the function. The for loop traverses every price in prices, and finalPrice will be set to the final price of the last price in prices.
8. The function will return an array containing final prices for each price in the array prices. discounted is an array declared using the keyword let, which means it has block scope. Then in the for loop it computes the final prices for each price in the array prices and push these final prices to the result array discounted.
9. This will result in an error. Notice that varible i is declared using keyword let and inside the for loop, so it only has the for loop scope. Attempting to read it after for loop will give us an error.
10. It will print the length of prices, since length is declared at the start of the function and thus has function scope, and since it's a constant then it can't be changed.
11. It will return an array containing the final prices of each price in prices. In the for loop, we calculate the final prices and push them into discounted. Notice that the const keyword only defines a constant reference to the array discounted.
12. A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher']['name']
    E. student.courseLoad[0]
13. A. string '32', since when a string S is added with a numeric value, that numeric value will be treated as a string and concatenated with S.
    B. number 1, since numeric conversion occurs with the math operation subtract and so string '3' will be treated as number 3.
    C. number 3, since when null is added with a numeric value, it will be converted to 0.
    D. string '3null', since when null is added with a string, it will be converted to a string 'null'
    E. number 4, since when true is added with numeric value, it will be converted to 1
    F. number 0, since numeric conversion occurs in math operations and both null and fasle are converted to 0.
    G. 3undefined, since undefined is added with a string, it will be converted to a string as well.
    H. NaN, since JavaScript will intepret '3' as number 3 and undefined as NaN and the result will be NaN
14. A. true, since JavaScript will convert string '2' to number 2 when comparing values of different types
    B. false, since JavaScript converts string '12' to number 12, and string '2' to number 2.
    C. true, since string '2' will be converted to number 2.
    D. false, since number 2 and '2' have different types and === checks for equality without type conversion
    E. false, since true will be converted to 1
    F. true, since Boolean(2) will be converted to true
15. == checks for equality after type conversion (if necessary), and === checks for equality without type conversion
17. The returned value will be [2,4,6]. We pass the function doSomething as the callback function, which multiplies the input by 2 and return it. In modifyArray, we walk through every element of array and call doSomething on it and push the result in the returned array.

19. The output would be in order: 1 4 3 2. First we print 1,4,3 directly without waiting, and then print 2 one second later.
    