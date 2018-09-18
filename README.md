## NUMBERS

- What is it?

The numeric sequence

- What does it do?

Counts

- How do you use it?

By using arithmetic operators

LESSON:

Here we’re going to look at how we can do some simple arithmetic using Python. In the following example we’re just adding two numbers; 4 + 4

Taking It Further - arithmetic operators.
As we can see, this prints out the result, which in this case is eight.

Play around with the above example try to some more addition. Also, instead of just using the addition operator, try out the following operators:

+-
*
/

Taking It Further
Try chaining more than two operators together and see what kind of results you end up with!

# Arithmetic Operators


The symbols that we used in the previous examples should look pretty similar to what we are familiar with from the maths that we learned in school. We call these symbols operators, and on each side of the operator, we have operands. Operators perform operations on operands. For example, 5 * 53. Here we are using the multiplication operator * on the operands 5 and 53.

Arithematic Operators:

+
-
*
/

In addition to the four operators we looked at previously, we also have the following:


**    %    //

exponent  modulo  floor division

We’ll leave Floor Division aside for now, and we’ll come back to it later in this lesson. Let’s take a look at the exponent and modulo operators. Exponent means to the power of. 
5 ** 5 would be 5 to the power of 5. Which is the same as writing 5 * 5 * 5 * 5 * 5. Similarly, 2 ** 3 would result in 8 as 2 multiplied by 2 is 4 and 4 multiplied by 2 is 8.

The modulo operator will divide the first number by the second and return the remainder. If we have 5 / 5, the answer will be 1 but if we were to use 5 % 5 then the answer would be 0. Similarly, if we had 18 % 7 the answer would be 4 because 7 goes into 18 twice (7 + 7 = 14) with a remainder of 4 (18 – 14 = 4).

The modulo torsoperator can be used when we need to find out if numbers are odd or even, and we would also use when working with time. If we wanted to convert minutes into hours and minutes. For example, we know that there are 60 minutes in an hour so if we wanted to figure out how many minutes are left over once we convert 10900 minutes into hours we would use 10900 % 60 (40 hours).

# Operator Precedence.

- What is it?

A set of rules that govern the flow of simplifying a mathematical expression.

- How do you use it?

Provides a set of rules that specify the sequence in which mathematical operations are executed by the computer.

- What does it do?

Chaining different mathematical operations together.

Creating a mathematical expression comprised of various operators will be subject to the operator precedence set of rules. These rules are used heavily in algebra. When working with a compound expression that is made up of multiple simpler expressions chained together, we need a way to determine which operations receive precedence. This operator precedence is determined using the BEMDAS order, which stands for Brackets, Exponents, Multiplication and Division, Addition and Subtraction. It is also sometimes referred to as BOMDAS, where the O stands for Orders.

- Let's go over this order of operations now. When the computer processes a mathematical expression with these operations, it follows these steps:

If the expression has any bracketed parts, start with the sub-expressions inside of these first (ie. - 1+1).

(1 + 1) ** 3
Calculate any exponents
Calculate multiplication and division - these 2 operations have the same precedence, since division is treated as multiplying by the reciprocal number
Calculate addition and subtraction - these 2 operations have the same precedence, since subtraction is treated as adding the negative number
If we were dealing with a sub-expression, get rid of the brackets now and proceed to calculate the outer expression, when only a single number is left, we're done.

1 + 1 =2 ** 3 = 8

# The print() Function 

- What is it?

Prints information to the program’s output

- What does it do?

Provides a means of outputting data

- How do you use it?

When we wish for our program’s to output information

LESSON:
We’ll cover functions in much more detail throughout the course, but for now, all we need to know about is the print() function.

my_variable = 5
print(my_variable)

Here we are invoking the print function. To do this, we use the function name, which in this instance is print followed by a pair of brackets or parentheses. Inside the parentheses, we’ll pass through an argument. When we wish for a function to do something with a variable, we pass it to a function as an argument. In this case, we have a value of 5 inside our my_number variable. Try to create other variables and print them out. Also, see what happens when you just pass numbers to the print function. Play around with the print function some more and see what happens. For example, try passing multiple arguments to the print function, and try to see what happens when you use multiple print functions. There’s much more to functions than what we’ve covered here, but we’ll continue to use functions throughout the course, and we’ll even look at creating our own functions in a later lesson.


## VARIABLES

- What is it?

Variables are analogous to “boxes” that we can use to store, modify and reference values in a computer program


- What does it do?

Allows us to give our values meaning, as well as the ability to recall those values whenever needed


- How do you use it?

Use variables to build up the data necessary for your computer program and persist it in memory

Fortunately, computers are much more than just fancy calculators. Computers have a hardware component called RAM (Random Access Memory). RAM is a storage medium for computers. Unlike a hard drive, RAM is volatile so any data stored in RAM will be lost after the computer has been shut down. RAM is used to store any data that is used by a computer program when it is running (also known as “being executed”). Not only do variables allow us to persist data that we may need for our program in memory, but it also allows us to provide meaningful names for the data that we’re storing. A variable acts as a placeholder in memory for a piece of data. The value of the data is stored in that placeholder. We can then use the name of that variable as a reference to that location in memory. Let’s try to create a variable now.

Here we have created a new variable called my_number. We have created a slot in memory for our variable. We then use the equal sign to assign the value of 5 to my_number which is called variable declaration as we are declaring the creation of a new variable. The equals sign is known as the assignment operator. We use this when we wish to assign values to a variable.

# Declaring Variables.

- What is it?

A means of persisting values in meaningful containers


- What does it do?

Allows us to give our values meaning, as well as the ability to recall those values whenever needed


- How do you use it?

Use variables to build up the data necessary for your computer program and persist it in memory


Throughout an application, we can create as many variables as we need. Although, there are a couple of rules that need to be followed when creating a variable. Variable names must start with a regular letter (lower or upper-case), and all further characters should be either letters or digits or underscores. There are many different ways in which we can name a variable. Some of the following can be used:

Any of these are acceptable. However, Python comes with it’s standard for writing readable code called PEP8 (https://www.python.org/dev/peps/pep-0008/). This standard only acts as guidelines for how code should be written to make all code as readable to all Python developers. PEP8 recommends using lowercase variable names and any variable names that contain spaces should use underscores as spaces.


# Variables & Arithmetic.

- What is it?

The means of storing and access values in variables using placeholder names


- What does it do?

Allows us to build up more complex expressions by giving our operands more meaningful names


- How do you use it?

Combine operators with variable based operands to perform arithmetic operations.
https://s3-eu-west-1.amazonaws.com/codeinstitute/fullstack/06-python-fundamentals/conten_assets/layout+of+python2-01.png

LESSON:
Because variables are just placeholders that reference the values stored in memory, we can continue to use them for arithmetic.
(+ - * //) - (Plus, Minus, Multiplication, Division)

Runnable Example
 
first_number = 10
second_number = 5

print(first_number + second_number)

prints 15
 
Now we’re just adding the values contained in two variables together. Notice how we’re adding two numbers together inside the function’s parentheses. Pieces of code that need to be evaluated are known as expressions Any expressions that we write inside of a function’s parentheses will be evaluated before the print function is invoked. The expression is evaluated, and the output is 15 meaning that 15 will be printed out.


## (VARIABLES - cont/...)


# Variable Reassignment - Part One

- What is it?

The ability to overwrite existing variables


- What does it do?

Allows us to make modifications to existing variables


- How do you use it?

By merely using the same syntax that we used to declare the variable!

## Variables Reassignment - Part One

We know that when we declare a variable called my_number and then print it out, it will print out the value stored in that variable. Watch what happens when we declare a second variable called my_number and print out the value.

 Runnable Example
 
 my_number = 5

my_number = 10

print(my_number)

Answer: prints 10


Expand

This time the output is 10. This is called variable reassignment. We use the variable name of my_variable to reference the value stored in that same memory location and update it accordingly. Then by the time that we pass the variable to the print function to value of my_variable has been updated to the value of 10. Therefore we can re-assign values to a variable as we choose.

What is it?

The ability to overwrite existing variables


What does it do?

Allows us to make modifications to existing variables


How do you use it?

By merely using the same syntax that we used to declare the variable!

# Variable Reassignment - Part Two

- What is it?

The ability to overwrite existing variables

- What does it do?

Allows us to make modifications to existing variables


- How do you use it?

LESSON:

By merely using the same syntax that we used to declare the variable!

The ways these operators work is by combining the arithmetic operator with the = assignment operator, as in the image to the left. We can use these operators for some shorthand operations.

 Addition AND (+ =)
 
 Subtraction AND (- =)
 
 Multiplication AND (* =)
 
 Division AND (/ =)
 
 Exponent AND (** =)
 
 Modulo AND (% =)
 
 Floor Division AND (// =)


 Runnable Example
 
variable_one = 5
variable_two = 8

variable_one += variable_two
print(variable_one)

Prints 13

Here we’ve declared two variables. Then we have decided to use the addition and operator to add the value from variable_two to variable_one and assign the result to variable_one, which is 13. Notice how variable_two isn’t affected by this operation. This same logic can be used with all of the other arithmetic operators. Try out the different operators in the above Repl.it session.

