---
layout: post
title: Take-aways from Intro JavaScript Course on Scrimba
---

# Welcome to my fifth entry

"let" is a way that you can you define variables. For example, "let firstName = nico". Let allows us to reassign variables, even using the same variable.

There are two types of comments in JavaScript: single line comments and multi-line comments

// This is a single-line comment in JavaScrip

/*
This is a multi-line comment in JavaScript
*/

"const" allows us to assign constant variables, or variables that do not change. This is useful for defining variables that cannot change such as the creation date for someting.

When trying to concatenate strings in Ruby you can reference variables in the below using curly braces:
`${firstName} ${lastName}`

A method is a function and JavaScript strings come with certain methods:
- .trim --> trims the extra spaces in the beginning and end of a string
- .length --> tells you have many characters the string is, including spaces
- .toUpperCase
- .toLowerCase
- .split --> will break a string into an array based on the empty spaces

Numbers also have many included methods as well. Here are some of them as well as other notes on numbers in JavaScript
- .toFixed(#) will give you a number with the number of decimals specified by the octothorpe. This will round numbers up. 
- .toFloat
- Numbers can appear as numbers or strings in the console. If they are numbers they will be blue. If they are strings they will be white.
- You can use parseInt() to pull out the first number out of a string if that string starts with a number. 
- You can use parseFloat()

typeof - you can use "typeof" to figure out what something is in JS:
- Example: "console.log(typeof something);"

Blooeans
- either they are true or false
- true is truthy
- false is falsey 
- null is falsey 
- undefined is falsey
- '' is falsey
- ' ' is truthy
- NaN = not a number = falsey
- negative numbers and positive numbers are truthy
- the only falsey value is zero

Arrays
- information organized in brackets [ ]
- they start on zero 
- you can define one by doing: "let example = [1, 2, 3]"
- .push() is a method that allows you add you figures to the array
- .pop() allos you to remove the last value of an array
- You can also override the value of a certain value by doing: "example[0] = 1"
- .forEach()

Objects are defined by curly braces: {}
- 


"%" is the modulo (or remainder) operator. It returns the remainder of the two numbers after division. If you are provided with two numbers, say A and B, A is dividend and by is the divisor.

"==" is equal to (here we are just checking to see if the values are equal to eachother)

"!==" is not equal to (here we are just checking to see if the values are not equal to eachother)
      
"===" is strictly equal to and requires BOTH the type and value to be the same between both objects

++ in JS means plus one

-- is JS means minus one

Below is an example of an if and else if syntax:
      let example = 5;

      if (example === 6) {
          console.log('Runs');
      } else if ( false ) {
          console.log('else if')
      } else {
          console.log('else')
      }

We can also use && (and) and || (or) in if statements

Switch statements - allows a variable to be tested for equality against a list of values. Each value is called a case, and the variable being switched on is checked for each case.

      let studentAnswer = 'D';

      switch(studentAnswer) {
          case 'A': 
              console.log('A is wrong.');
              break;
          case 'B' :
              console.log('B is wrong.');
              break;
          case 'C':
              console.log('C is correct.');
              break;
          default: 
              console.log('Not a real answer.');
      } 
      
Loops in JavaScript, there are several types:
- For loops
- While loops run until some value is false
- Do while loops: runs at least once

Functions: when you solve problems, typcially you want to reuse code and call it as a function. See example below:

        function add(num1, num2) {
            return num1 + num2;
        }

        console.log(add(10, 6));


      




