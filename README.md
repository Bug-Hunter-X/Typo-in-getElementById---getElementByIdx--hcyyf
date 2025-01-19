# Uncommon HTML Error: Typo in getElementById

This repository demonstrates a subtle but common error in JavaScript when interacting with the DOM.  The example uses a simple typo in the `getElementById` method, leading to a runtime error. The solution provides the correct implementation.

## Bug
The `bug.html` file contains a typo in `document.getElementByIdx()`, which results in a JavaScript error because `getElementByIdx` does not exist. 

## Solution
The `bugSolution.html` file provides the corrected code, using the correct `document.getElementById()` method to access and modify the element.