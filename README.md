# ArrayIndexOutOfBoundsException in Java
This repository demonstrates a common Java programming error: the `ArrayIndexOutOfBoundsException`. The error occurs when the program tries to access an array element using an index that is outside the valid range of indices for that array.  The `bug.java` file contains the erroneous code, while `bugSolution.java` provides the corrected version.

**Problem:** The loop in `bug.java` iterates one time too many, causing an attempt to access `arr[5]` in an array of size 5 (valid indices are 0-4). 

**Solution:** The corrected loop in `bugSolution.java` ensures that the index `i` remains within the valid bounds of the array by using the condition `i < arr.length`. 