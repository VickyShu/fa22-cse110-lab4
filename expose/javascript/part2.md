1. 3, because console.log(i) is outside the for loop, then it will print out the length of the prices, which is 3.
2. 150, because console.log(discountedPrice) is outside the for loop, then it will print out the discountedPrice of the last price inside prices, which is 300*(1-0.5)=150.
3. 150, because console.log(finalPrice) is outside the for loop, then it will print out the rounded discountedPrice of the last price inside prices.
4. [50, 100, 150], it will return all rounded discountedPrices from the prices.
5. ERROR, because variable i is declared inside a code block using let, it is not defined outside that for loop.
6. ERROR, because variable discountedPrice is declared inside a code block using let, it is not defined outside that for loop.
7. 150, because variable finalPrice is declared inside that function using let, it is defined inside the whole function.
8. [50, 100, 150], it will return all rounded discountedPrices from the prices.
9. ERROR, because variable i is declared using const, it is not allowed to be reassigned.
10. 3, it will return the length of the prices, which is 3.
11. [50, 100, 150], it will return all rounded discountedPrices from the prices without attempting to change the address of discounted.
12. A: student.name;
    B: student['Grad Year'];
    C: student.greeting();
    D: student['Favorite Teacher'].name;
    E: student.courseLoad[0];
13. A: ‘3’ + 2 -> '32', since integers map to their exact string representation.
    B: ‘3’ - 2 -> 1, the string '3' is automatically converted to a numeric value before the subtraction is performed, because the - operator requires numeric operands.
    C: 3 + null -> 3, since 3 is a number, + operator converts null to a number, treating it as 0.
    D: ‘3’ + null -> '3null', when one or both of the operands is a string, the + operator performs string concatenation. 
    E: true + 3 -> 4, since true maps to 1.
    F: false + null -> 0, false maps to 0 and null maps to 0.
    G: '3' + undefined -> '3undefined', when one or both of the operands is a string, the + operator performs string concatenation.
    H: '3' - undefined -> NaN, since '3' is converted to 3 and undefined maps to NaN, and any arithmetic operation involving NaN will result in NaN.
14. A: ‘2’ > 1 -> true, since string '2' becomes a number 2
    B: ‘2’ < ‘12’ -> false, this is a dictionary comparison, first char "2" is greater than the first char "1".
    C: 2 == ‘2’ -> true, string '2' becomes a number 2, which is the same as 2.
    D: 2 === ‘2’ -> false, 2 is a number and '2' is a string. Thery have different type.
    E: true == 2 -> false, true maps to 1, which is not equal to 2.
    F: true === Boolean(2) -> true, Values that are 0, an empty string, null, undefined, and NaN, become false. Other values become true. True and true have the same type.
15. A strict equality operator === checks the equality without type conversion. A non-strict equality operator == checks the equality with type conversion.
17. [2, 4, 6], modifyArray function goes through each value in [1, 2, 3]. For each iteration, it calls the function doSomething which multiplies each value by 2. Then, it pushes the updated values into the newArr and returns the newArr. So we get [2, 4, 6].
19. 1
    4
    3
    2