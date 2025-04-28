1) The value of i, which is prices.length; will be logged to the console. This is because varaibles declared with var don't have block scoping, so i can be accessed outside of the for loop.
2) The value of discounted price for the last item in the array. This is because variable declared with var don't have block scoping, so the discounted price will persist outside of the for loop.
3) The value of the final price for the last item in the array. This is because variables declared with var don't have block scoping, so the final price will persist outside of the for loop.
4)  
5) This will result in an error. This is because i was declared with let meaning that it is only valid within the scope of the for loop. 
6) This will result in an error. This is because discountedPrice is declared with let in the for loop, meaning that it is only valid within the scope of the for loop
7) This will return the value of the final price for the last item in the array. This is because the variable is declared globally within the function so it will be able to be accessed at that line.
8) This will return the array of discounted values. This is because the array is declared globally within the scope of the function.
9) This will cause an error. This is because the variable i is declared with a let, meaning that it can only be accessed within the scope of the for loop.
10) This will result in the length of the array, 3, being printed. This is because the variable is declared with const globally within the scope of the function so it can be accessed. 
11) This will return the array of newly discounted prices. Since discounted is defined globally in the scope of the function it can be accessed everywhere throughout the function
12)  
   A) student.name
   B) student["Grad Year"]
   C) student.greeting()
   D) student["Favorite Teacher"].name
   E) student.courseLoad[0]
13) 
    1)  '32' - this is because integers map to their string representation and the '+' is used as concatenation
    2)  1 - this is because javascript tries to convert both operands to integers when using '-'
    3)  3 - this is because null is interperted as 0
    4)  '3null' - this is because javascript treats both operands as strings and concatenates them
    5)  4 - this is because true is intereperted as 1
    6)  0 - this is because both false and null are interpreted as 0
    7)  '3undefined' - this is because javascript treats the undefined as a string and concatenates the operands
    8)  NaN - this is because tries to convert both operands to integers when using the '-' operator, but undefined does not convert to a numerical value
14)  
     1)   true - this is because javascript converts strings to integers first when using compairisons
     2)   false - when both sides are strings, javascript does string comparision and compares them alphabetically
     3)   true - this is because this is loose equivelance so javascript converts both operands to the same type
     4)   false - this is because this strict comparision so a string and number are being compared, so they will not be equivelant
     5)   false - this is because true would convert to 1, which is not 2
     6)   true - this is because all numbers beside 0 cast to true
15)  == is loose equality so values are converted to the same data type before comparing. === is strict equality so both values are compared without converting data types
16)  in js file
17)  [2, 4, 6] is the result - this is because the callback function is applied to each value in the array as it is iterated over. The array is looped over and each value in the array is passed as a parameter into the callback function which returns that value multiplied by 2
18)  in js file
19)  1 \n 2 \n 3 \n 4- it will print this sequence of numbers each on a newline
