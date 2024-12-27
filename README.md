# Uninitialized Data Item in COBOL

This repository demonstrates a common error in COBOL programming: using uninitialized data items.  The `bug.cob` file shows a program that attempts to move the contents of an uninitialized data item to another. The `bugSolution.cob` file provides the corrected version with proper initialization.

**Problem:** In COBOL, data items are not automatically initialized.  Accessing uninitialized data can lead to unpredictable results, program crashes, or incorrect outputs.

**Solution:**  Explicitly initialize data items before using them in operations.  This involves assigning a specific value (e.g., spaces, zeros) to the data item to establish a known starting state.

The example code in this repo illustrates the problem and demonstrates a correct approach to prevent it.