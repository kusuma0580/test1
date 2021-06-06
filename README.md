# test1
* Learning how to use git and github.
* Learning how to code in colab.
* Created a new repository named test1 and copied file containing python code,which is created using colaboratory.
* Written some code in python to find factorial of the number in different methods.

* What is a factorial?
* Factorial is a non-negative integer.It is the product of all positive integers less than or equal to that number you ask for factorial.
* It is denoted by exclamation sign "!".
* Example:
         n!=n*(n-1)*(n-2)*.......1
         4!=4*(4-1)*(4-2)*(4-3) {(4-3) which is equal to 1}
         4!=4*3*2*1
           =24.
* The factorial of 4 is 24.
* Note:The factorial of 0 is always "1".

* Methods used:
  (1)using for loop
  (2)using a function
  (3)using recursion method
  (4)using built-in function
  
 * (1)Using for loop:
      To find factorial of a given number,let us form a for loop over a range from 1 to itself.
      Remember that range() function excludes the stop value.Hence stop value should be one more than the input number.
      Each number in range is cumulatively miltiplied in a variable factorial which is assigned to 1.
 
 * (2)Using a function:
      Take a number as input from the user and stored in variable for finding factorial.
      Declare a python function to find the factorial.inside the function, declare the variable fact and initialise as 1.
      Inside the function, find the find the factorial of a given number using for loop in python.
      call the factorial() and return the result.
      
 * (3)Using recursion method
      * Recursion:
        The process in which a function calls itself directly or indirectly is called recursion.The corresponding function is called as recursive function.
      Take a number from the user and store it in a variable.
      Pass the number as an argument to a recursive factorial function.
      call the function recursively with the number minus 1 multiplied by the number itself.
      Then return the result and print the factorial of a number.
      Example:
             factorial(5)
             
             return 5 * factorial(4) = 120
                 ^
             return 4 * factorial(3) = 24
                 ^
             return 3 * factorial(2) = 6
                 ^
             return 2 * factorial(1) = 2
                 ^
                 1
      
 
 * (4)Using built-in function:
      In this case we can directly use factorial function which is available in math module.
      We need not write the code for factorial functionality rather directly use the 'math.factorial()'.
      That also take care of negative numbers and fractional numbers scenario.
