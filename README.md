# Hidden HTML Element Bug

This repository demonstrates a common yet easily overlooked bug in HTML/JavaScript interaction:  an element is hidden using JavaScript, but there's no provision to make it visible again. The bug lies in the `myFunction()` which hides the div, but lacks a way to reverse the action. 

## Bug Description

The `bug.html` file contains a div that is hidden when a button is clicked.  However, once hidden, there's no way to show it again, resulting in a permanently hidden element.  This is a classic example of state management oversight. 

## Solution

The `bugSolution.html` demonstrates a corrected version.  It adds a toggle functionality, allowing the div to be shown and hidden alternately.