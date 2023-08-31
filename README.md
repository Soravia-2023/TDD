# Test Driven Development

This is a template for the TDD exercise. There is a simple test-class referring an implementation to verify that everything is setup correctly.

<b>Initial Task</b>
Create a simple String calculator with a method signature:

  int add(String numbers)

The method can take up to two numbers, separated by commas, and will return their sum.
For example “” or “1” or “1,2” as inputs.(for an empty string it will return 0)

Think about the design first
Write down a list of examples
Remember to solve things as simply as possible so that you force yourself to write tests you did not think about
Remember to refactor after each passing test



<b>Feature 1</b>

Provide a second default delimiters for separating the numbers: , or \n

<b>Feature 2</b>

Support additional delimiters in the following format

   “//[delimiter]\n[numbers...]”

<b>Feature 3</b>

Calling add() with a negative number will throw an exception with the message “negative number are not allowed”. The exception should contain the negative number that was passed. If there are multiple negative numbers, list all of them in the exception message

<b>Feature 4</b>

Numbers bigger than 1000 should be ignored, so adding 2 + 1001  = 2

<b>Feature 5</b>

Delimiters can be of any length:
 “//[***]\n1***2***3” should return 6
