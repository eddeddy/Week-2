ISD lab sheet week 2

Github: 1) If you haven’t done so yet, please sign up for Github https://github.com/

2) Create a repository for your source code

3) Commit (upload) the code from week 1 to your repository

For the practical part of this lab please save the Python programs that you create and take screenshots of the execution (evaluation) of your programs. Commit (upload) all source code you create to your code repository.

1. What will the output be from the following code?

num = 4

num*=2

num1=num+2

num1+=3

print(num1)

13

2. What do the following lines of code output? Why do they give a different answer?

print(2 / 3)

print(2 // 3)

Because single / is for quotient which give float number and bouble // is for integer quotient which give integer number.

3. All of the variable names below can be used. But which of these is the better variable name to use?

A a Area AREA area areaOfRectangle AreaOfRectangle

a – because is more esay to use

4. Which of these variables names are not allowed in Python? (More than one might be wrong.)

apple APPLE Apple2 1Apple account number account_number account.number accountNumber fred Fred return return_value 5Return

GreatBigVariable greatBigVariable great_big_variable great.big.variable 2x

account number – because because it has space between words

return – because it’s keyword

5. Explain the mistake in the following code:

radius = input("Radius:")ßthis is wrong because we have to put int(input("Radius:"))

x = 3.14

pi = x

area = pi * radius ** 2

6. Explain the mistake in the following code:

x = 4

y = 5

a = 3(x + y)ßthis it is wrong , the good expression is a = 3*(x+y)

7. Explain the mistake in the following code:

radius = input(float("Enter the radius:"))ß because the float must be placed before input

8. Why does this code not calculate the average?

print(3 + 4 + 5 / 3)

Because the program do first 3+4 and after that do 5/3

9. Consider the following code:

x = 19.93

y = 20.00

z = y – x

print(z)

The output is 0.0700000000028 Why ?

Improve the code so that the output is to two decimal places. round(z,2); print(“%.2f”%z)

10. Find at least three compile-time errors:

int x = 2 ß We should not put int

Print (x, squared is, x * x)ß because we have to put quotes

xcubed = x *** 3ßbecause we can’t put three * , we can do x*x*x

11. Find two run-time errors:

from math import sqrt

X = 2

Y = 4

print(“The product of “, x, “and”, y, “is”, x + y)

print(“The root of their difference is “, sqrt(abs(x – y)))

First mistake is varibles X and x , and other mistake is the product it’s x*y not x+y

12. Write statements to prompt user for their name and age

Write a print statement to output:

Hello ____, next year you will be ____ years old!

13. Given that radius is 2 and area is calculated as 12.5678, use string format operators to print the values of the variables radius and area so that the output looks like this:

Radius is: 2

Area is: 12.57

14. What are the values of the following expressions, assuming that p is 17 and q is 18?

i. p // 10 + p % 10 = 8

ii. p % 2 + q % 2 = 5

iii. (p + q) // 2 = 17

iv. (p + q) / 2.0 = 17.5
