# COBOL Numeric Overflow Bug

This repository demonstrates a common but easily missed bug in COBOL programs involving numeric overflow.  When performing arithmetic operations, if the result exceeds the size defined for the numeric field, the result can be truncated or produce unexpected behavior.  The example showcases how adding 1 to a field already at its maximum value can lead to an incorrect or unexpected result.

The `bug.cob` file contains the erroneous code, while `bugSolution.cob` provides a corrected version demonstrating how to handle potential overflow using appropriate data types and error handling techniques.  Understanding and addressing these issues is crucial for ensuring the reliability and accuracy of COBOL applications.