# Off-by-One Error in Java

This repository demonstrates a common off-by-one error in Java when iterating over arrays.  The error occurs because the loop condition `i <= arr.length` should be `i < arr.length`.  The solution demonstrates how to correctly iterate over the array.

The `Bug.java` file contains the erroneous code, while `Solution.java` provides the corrected version. 