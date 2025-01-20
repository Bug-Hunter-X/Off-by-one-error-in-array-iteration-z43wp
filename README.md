# Off-by-one Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over an array. The error leads to an `ArrayIndexOutOfBoundsException` at runtime.  The solution shows how to correct the error to ensure safe and accurate array traversal. 

**Bug:** The provided Java code attempts to iterate over an array using a loop condition that includes the array's length, resulting in an out-of-bounds access.

**Solution:** The fix modifies the loop condition to ensure that only valid array indices are accessed.