---
layout: post
title: Things I learned from The Ruby Koans
---

Here are three things I learned from [The Ruby Koans](http://rubykoans.com/):
1) Curly brackets are used for many things in Ruby so we have to be careful where they are put. When curlies come right next to a method name Ruby can interpret it as a block.
2) "assert_raise":Assertions are always in the test code. There is no reason for assertions to be in the application code. They allow you to cause an exception.
3) You can use begin, rescue and end to flag errors. Only do it when you legitimately need exceptions to come in. Don't use it to sweep issues under the rug. 
4) When dealing with strings, applying methods to them does not change the object/string. For example, if a = "hello" then a.reverse does not change the string. 
5) inheritance: super is a key word that allows you to access the ancestor.
6) The main use for private and protected is adding the private keyword in a class.  
7) New terms to look into later: shovel operator, superclass.


