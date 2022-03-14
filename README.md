# Exercise 01 Calculator 
### Deadline 17.03.2022

Your task is to program a little command-line calculator with user input.
The calculator can perform integer and floating-point operations.

The following calculations should be provided with integers:
* addition
* subtraction
* division
* modulo
* check if a number is odd or even (reuse your methods)

In addition to this the following operations should be performed with floating points:
* addition
* subtraction
* division

## Task 1 Input
First, the user has to choose which operation he wants to perform and on which numbers.
Two input variables are sufficient.

An example could look like this:

~~~
Choose between floating-point and integer operations
1) integer
2) floating

Input the according number:
2

You have chosen floating points
Input the first number:
3.5
Input the second number:
4.89

You have the following options with floating points:
1) addition
2) subtraction
3) division

~~~

> Use **only one** `Scanner` for the whole user input (reuse it).

## Task 2
Implement all the different operations and print the result.

~~~
...

Result: 8.39

~~~

## Task 3 Bonus
Pretty print the result
The result should look like this example for an addition

~~~
3.5 + 4.89 = 839
~~~

## Task 4 Bonus
Implement a method that returns a random positive integer.
Do not forget to add it to the menu.

The math library from Java provides such a random number function. 

~~~java
int randomNumber = Math.abs(new Random().nextInt());
~~~

Can you guess what `Math.abs()` does? 

----

Stick to a clean style, have coding conventions in mind, and most importantly **do not repeat yourself**.
