# R Subsetting Error: Logical Subscript Too Short

This repository demonstrates a common error in R programming related to subsetting data frames using logical vectors.  The error arises when the length of the logical vector used for subsetting does not match the number of rows in the data frame.  The code provided shows the error and the solution for correcting it.

## Bug Description

The script `bug.R` attempts to subset a data frame using a logical vector shorter than the number of rows in the data frame.  This results in an error.

## Solution

The script `bugSolution.R` provides a corrected version by ensuring the logical vector is of the correct length. This version uses recycling to correctly subset the data.
