# Off-by-One Error in While Loop

This repository demonstrates a common off-by-one error in a Java while loop. The loop's counter variable is incremented before the check, resulting in an unexpected loop termination.

## Bug

The `Bug.java` file contains the buggy code. The while loop iterates only 4 times instead of the expected 5 times.