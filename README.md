# Uncommon HTML Error: TypeError when accessing non-existent element

This repository demonstrates an uncommon error in HTML that arises when JavaScript attempts to access an HTML element that does not exist in the DOM.

## Description
The code in `bug.html` attempts to get the `textContent` of an element with the ID 'nonExistentElement', which doesn't exist. This results in a `TypeError` being thrown.

## Solution
The solution in `solution.html` adds appropriate error handling to check if the element exists before attempting to access its properties. This prevents the `TypeError` from occurring.