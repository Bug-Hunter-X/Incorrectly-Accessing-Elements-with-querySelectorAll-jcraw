# Incorrectly Accessing Elements with querySelectorAll
This example demonstrates a common error when using `document.querySelectorAll`.  `querySelectorAll` returns a NodeList, which is similar to an array but isn't accessed in the same way. Attempting to directly modify the `innerHTML` property will result in an error. 

## Bug
The provided `bug.html` file shows the incorrect way of accessing the element by using querySelectorAll.

## Solution
The `bugSolution.html` file demonstrates the corrected approach.  The NodeList is accessed as an array to access the first element (index 0) before modifying the `innerHTML`.