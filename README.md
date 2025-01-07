# JavaScript Null Handling Bug

This repository demonstrates a common JavaScript error related to handling null values and provides a corrected version. The original code fails to properly handle null inputs, resulting in unexpected behavior or errors. The solution provides a robust way to check for null values before performing operations.

## Bug Description

The original `foo` function doesn't explicitly handle cases where either `a` or `b` is `null`.  When one or both inputs are `null`, this leads to incorrect or unexpected output.

## Solution

The solution adds a check at the beginning of the function to handle `null` inputs explicitly. This prevents unexpected behavior when dealing with null values.