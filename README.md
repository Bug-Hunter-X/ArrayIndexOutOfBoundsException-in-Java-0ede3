# ArrayIndexOutOfBoundsException in Java

This repository demonstrates a common Java error: the `ArrayIndexOutOfBoundsException`. The `BuggyArray.java` file contains code that causes this exception. The `FixedArray.java` file provides a corrected version.  The error occurs due to an off-by-one error in the loop's termination condition.  This is a frequently encountered problem when working with arrays and loops in Java.

## How to Run
1. Clone this repository.
2. Compile and run `BuggyArray.java` to observe the exception.
3. Compile and run `FixedArray.java` to see the corrected behavior. 

## Lessons Learned
* Always carefully check loop termination conditions when working with arrays.
* Pay close attention to array indices; they are zero-based.
* Use a debugger to step through your code and identify the source of the error.