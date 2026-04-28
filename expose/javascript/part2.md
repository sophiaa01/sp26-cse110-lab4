# Part 2. A Little More of a Challenge
1. Line 12 outputs 3 because the variable "i" can be accessed anywhere in the function and the last assignment of "i" was the length of the list, 3.
2. Line 13 outputs 150 because the variable "discountedPrice" can be accessed anywhere in the function and the last assignment of the variable was 150.
3. Line 13 outputs 150 because the variable "finalPrice" can be accessed anywhere in the function and the last assignment of the variable was 150.
4. This function will return the discounted prices, but it doesn't output the values because it wasn't explicitly logged.
5. The code throws an error because the variable "i" is defined with the let keyword. This means that code outside the scope of "i" is not able to access it.
6. The code throws an error because the variable "discountedPrice" is defined with the let keyword. This means that code outside the scope of "discountedPrice" is not able to access it.
7. Line 14 outputs 150 because it is in the scope of "finalPrice".
8. This function will return the discounted prices, but it doesn't output the values because it wasn't explicitly logged.
9. The code throws an error because the variable "i" is defined with the let keyword. This means that code outside the scope of "i" is not able to access it.
10. Line 12 outputs 3 because because it is in the scope of "length".
11. This function will return the discounted prices, but it doesn't output the values because it wasn't explicitly logged.
12. 
    - A. student.name
    - B. student['Grad Year']
    - C. student.greeting()
    - D. student['Favorite Teacher'].name
    - E. student.courseLoad[0]
13. Arithmetic
     - A. '32', integers map to their exact string representation
     - B. 1, strings are converted to numbers
     - C. 3, null becomes 0
     - D. '3null', null becomes 'null'
     - E. 4, true becomes 1
     - F. 0, false becomes 0 and null becomes 0
     - G. '3undefined', undefined becomes "undefined"
     - H. NaN, '3' is converted to a number and undefined becomes NaN
14. Comparison
     - A. true, '2' is converted to a number and it is greater than 1
     - B. false, strings are compared letter-by-letter and 2<1 is false
     - C. true, '2' is converted to a number
     - D. false, strict equality operator checks equality without type conversion
     - E. false, true becomes 1
     - F. true, Boolean(2) becomes true
15. Different types are converted to numbers by the equality operator '=='. But a strict equality operator '===' checks equality without the type conversion.
16. 21 45 5 2
17. The result will be [2, 4, 6]. We pass in the function 'doSomething' and it is 'called back' later.
18. Code in part2-question18.js
19. 1 4 3 2