# ActionScript Array Out-of-Bounds Error
This repository demonstrates a common error in ActionScript related to array indexing.  ActionScript arrays, like many other languages, are zero-indexed. Attempting to access an element using the length of the array as the index will result in an error because the valid indices range from 0 to length-1.

## Bug Description
The `bug.as` file contains a function that attempts to access the last element of an array using `myArray[myArray.length]`. This will cause an error because the index is out of bounds. The correct way to access the last element is using `myArray[myArray.length - 1]`.

## Solution
The `bugSolution.as` file provides the corrected code, showing the proper method of accessing the last array element.
