Lab 3a
======

Submit your finished code to the Dropbox. You will need to pass off the lab with the TA or tutor during their office hours (their information is in the CS 105 Course Information section of the Class Resources module), or the instructor in class. Follow the CS 105 Formatting Guide which is also found in the CS 105 Course Information section.

Read the instructions carefully. Make sure your output matches the example run.

Objectives:
===========

In this lab, you will learn how to do the following:

-   Use if, else if, and else statements
-   Use the logical 'and' operator &&
-   Translate categories described in a table to logical code

Structure:
==========

Create the following structure in Eclipse for this lab.

-   **Package Name: w**eek3
-   **Class Name: **Lab3a

Program: Shirt Sizes
====================

Sometimes it can be difficult to order a men's shirt online.  It would be helpful to have a program tell you what size shirt you should buy based on the measurement of the customer's chest.

Write a program that will ask the user for the customer's chest size in inches.  The program will then display what shirt size should be ordered.

Use the following table to determine the appropriate shirt size:
<img width="565" alt="image" src="https://github.com/Ensign-College/CS105Lab3a/assets/130691832/be54a16c-34df-485f-b1a5-54db24de1d3b">


In this lab, you will follow the step by step instructions below to write the program.

**Step 1:**

-   Using the Scanner, use an in.nextLine() statement to prompt the user for the measurement of the customer's chest. Store the user's input into a variable called input

**Step 2:**

-   Convert the user input into an integer using Integer.parseInt() and store the converted value into a variable called chestSize.

**Step 3:**

-   Write an*** if*** statement that checks to see if ***chestSize*** is less than 38 inches.

**Step 4:**

-   If step 2 is true, print the appropriate shirt size (S).

**Step 5:**

-   Use an ***else if*** statement to see if ***chestSize*** is greater than or equal to 38 inches and less than 40 inches. (Remember that **&&** is the 'and' operator)

**Step 6:**

-   If step 4 is true, print the appropriate shirt size (M).

**Step 7:**

-   Use an ***else if*** statement to see if ***chestSize*** is greater than or equal to 40 inches and less than 43 inches.

**Step 8:**

-   If step 6 is true, print the appropriate shirt size (L).

**Step 9:**

-   Use an ***else if*** statement to see if ***chestSize*** is greater than or equal to 43 inches and less than 46 inches.

**Step 10:**

-   If step 8 is true, print the appropriate shirt size (XL).

**Step 11:**

-   Use an ***else*** statement to print the appropriate shirt size (XXL) of none of the above conditions are true.

Key program requirements:
=========================

-   Use if, if else, and else statements to determine the appropriate output
-   Output should look like the example run
-   Submit the following .java file:
-   -   Lab3a.java

Example Run:
============

*In this program, we will determine a man's shirt size based on the measurement in inches of the customer's chest.*\
*Please enter the customer's chest measurement in inches: *\
*30*\
*A customer with a chest measurement of 30 inches needs to order a size S.*

*----------------------------*

*In this program, we will determine a man's shirt size\ based on the measurement in inches of the customer's chest.*\
*Please enter the customer's chest measurement in inches: *\
*38*\
*A customer with a chest measurement of 38 inches needs to order a size M.*

*----------------------------*

*In this program, we will determine a man's shirt size\ based on the measurement in inches of the customer's chest.*\
*Please enter the customer's chest measurement in inches: *\
*41*\
*A customer with a chest measurement of 41 inches needs to order a size L.*

*----------------------------*

*In this program, we will determine a man's shirt size\ based on the measurement in inches of the customer's chest.*\
*Please enter the customer's chest measurement in inches: *\
*44*\
*A customer with a chest measurement of 44 inches needs to order a size XL.*

*----------------------------*

*In this program, we will determine a man's shirt size\ based on the measurement in inches of the customer's chest.*\
*Please enter the customer's chest measurement in inches: *\
*46*\
*A customer with a chest measurement of 46 inches needs to order a size XXL.*
