# R Subsetting Error: Handling Missing Columns

This repository demonstrates a common error in R when subsetting data frames using character vectors of column names.  The code attempts to select columns "a", "d", and "b", but column "d" does not exist. This leads to an error.

The `bug.R` file contains the erroneous code. The `bugSolution.R` file provides a corrected version that gracefully handles the case of missing columns.

This example highlights the importance of robust error handling when working with data.
