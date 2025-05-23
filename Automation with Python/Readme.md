## Python
---
Python is a high-level, interpreted programming language known for its clear syntax and readability. It supports multiple programming paradigms, including object-oriented, procedural, and functional programming. Python is widely used in web development, automation, data science, artificial intelligence, and cybersecurity due to its simplicity and large standard library.

**1.Variable**<br>
**2.Loops**<br>
**3.Functions**<br>
**4.Data Strucures**<br>
**5.if statements**<br>
**6. Files**<br>

**Mathematical Operators**

Let's now study about the mathematical operators and how they can be applied to python. Like a calculator, there are operations such as adding, subtracting, multiplying, and diviving; using python,

| Operator      | Syntax | Example        |
|---------------|--------|----------------|
| Addition      | `+`    | `1 + 1 = 2`     |
| Subtraction   | `-`    | `5 - 1 = 4`     |
| Multiplication| `*`    | `10 * 10 = 100` |
| Division      | `/`    | `10 / 2 = 5`    |
| Modulus       | `%`    | `10 % 2 = 0`    |
| Exponent      | `**`   | `5 ** 2 = 25`   |

And now we can some basic mathematical operators, lets move on to comparision opetators; these play a big part in python and will be built upon when we look at _loops_ and _if statements_.

| Symbol                     | Syntax |
|----------------------------|--------|
| Greater than               | `>`    |
| Less than                  | `<`    |
| Equal to                   | `==`   |
| Not Equal to               | `!=`   |
| Greater than or equal to   | `>=`   |
| Less than or equal to      | `<=`   |


# Variabls and Data Types

Variables allow you to store and update data in a computer program. You have a variable name and store data to that name.

<pre lang="md"> food = "ice cream" <br>
 money = 2000 
  </pre>
In the example above, we have 2 variables. The variable name "food" stores the string (words) ice cream, while another variable called "money" stores a number (2000).

One another example:
<pre lang="md"> age = 30<br>
age = age + 1<br>
print(age)
</pre>

**DATA TYPE**<br>
**String** - Used for combinations of characters, such as letters or symbols<br>
**Integer** - Whole numbers<br>
**Float** - Numbers that contain decimal points or for fractions<br>
**Boolean** - Used for data that is restricted to True or False options<br>
**List** - Series of different data types stored in a collection<br>

# Logical and Boolean Operators
Logical operators allow assignment and comparisons to be made and are used in conditional testing (such as if statements).
| Logical Operation       | Operator | Example       |
|-------------------------|----------|---------------|
| Equivalence             | `==`     | `if x == 5`   |
| Less than               | `<`      | `if x < 5`    |
| Less than or equal to   | `<=`     | `if x <= 5`   |
| Greater than            | `>`      | `if x > 5`    |
| Greater than or equal to| `>=`     | `if x >= 5`   |

Boolean operators are used to connect and compare relationships between statements. Like an if statement, conditions can be true or false.

| Boolean Operation                             | Operator | Example                                             |
|----------------------------------------------|----------|-----------------------------------------------------|
| Both conditions must be true                 | `AND`    | `if x >= 5 AND x <= 100` → True if x is between 5 and 100 |
| Only one condition needs to be true          | `OR`     | `if x == 1 OR x == 10` → True if x is 1 or 10        |
| Opposite of a condition                      | `NOT`    | `if NOT y` → True if `y` is False                    |

**Examples:**__
<pre lang="md">
 a=1<br>
 if a==1 or a>10:<br>
     print("a is either 1 or above 10")
</pre>

**OUTPUT**
`a is either 1 or above 10`

<pre lang="md">name = "bob" <br>
 hungry = True <br>
 if name == "bob" and hungry == True: <br> 
      print("bob is hungry") <br>
 elif name == "bob" and not hungry: <br>
      print("Bob is not hungry") <br>
 else: <br>
      print("Not sure who this is or if they are hungry")</pre>

**OUTPUT**
`bob is Hungry`

# If Statements
Using "if statements" allows programs to make decisions. They let a program chose a decision based on a condition. Below is an example of how an if statement can be used to determine the section of code (which print statement) to use.

<pre lang="md">
if age < 17:<br>
    print('You are NOT old enough to drive')<br>
else:<br>
    print('You are old enough to drive')<br>
</pre>

# Loops

In programming, loops allow programs to iterate and perform actions a number of times. There are two types of loops, for and while loops.

**While Loops**<br>

Let's begin by looking at how we structure a while loop. We can have the loop run indefinitely or (similar to an if statement) determine how many times the loop should run based on a condition.
<pre lang="md">
i = 1<br>
while i <= 10:<br>
     print(i)<br>
     i = i + 1<br>
</pre>

**For Loops**<br>

A for loop is used to iterate over a sequence such as a list. Lists are used to store multiple items in a single variable, and are created using square brackets  (see below). Let's learn through the following example:

<pre lang="md">
websites = ["facebook.com", "google.com", "amazon.com"]<br>
for site in websites:<br>
     print(site)
</pre>

# Functions
 A function is a block of code that can be called at different places in your program.
 You could have a function to work out a calculation such as the distance between two points on a map or output formatted text based on certain conditions. Having functions removes repetitive code, as the function's purpose can be used multiple times throughout a program.

<pre lang="md">
def sayHello(name):<br>
     print("Hello " + name + "! Nice to meet you.")<br>

sayHello("ben")
</pre>

**OUTPUT**: `Hello Ben! Nice to meet you`
