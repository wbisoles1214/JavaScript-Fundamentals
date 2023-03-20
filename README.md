# JavaScript Fundamentals

## Learning objectives

1. What is JavaScript?
2. How do we declare a variable?
3. Which variable keyword should you use when?
4. What are the rules for naming variables?
5. What are operators, operands, and operations?
6. What is concatenation and what happens when you add numbers and strings together?
7. What are the different types of operators in JavaScript?
8. What are operator precedence values?
9. What are the increment/decrement operators?
10. What is the difference between == and ===?
11. What is the difference between prefixing and postfixing them?
12. What are assignment operators?
13. What is the Unary Plus Operator?

### An Introduction to JavaScript

- JavaScript was initially created to “make web pages alive”.
- "LiveScript"
- ECMAScript

### How to Run JavaScript Code?

### Variables

- are used to store information / a "named storage" for data
- An online shop ==> the information might include goods being sold and a shopping cart
- A chat application ==> the information might include users, messages, and much more.

#### Limitations when naming variables in JavaScript

1. The name must contain only letters, digits, or the symbols $ and \_.
2. The first character must not be a digit.

- let ==> is a modern variable declaration
- var ==> is an old-school variable declaration. Normally we don’t use it at all.
- const ==> is like let, but the value of the variable can’t be changed.

#### Exercises

1. Working with variables

- Declare two variables: admin and name.
- Assign the value "John" to name.
- Copy the value from name to admin.
- Show the value of admin using alert.

2. Giving the right name

- Create a variable with the name of our planet. How would you name such a variable?
- Create a variable to store the name of a current visitor to a website. How would you name that variable?

3. Examine the following code:

const birthday = '18.04.1982';

const age = console.log(birthday);

### Numbers

- are the building blocks of programming logic
- +, -, \*, /, \*\*, %, ++, --
- assignment (=), equality (==), strict equality (===)