# Tcl: Potential Division by Zero Error

This repository demonstrates a potential division by zero error in a Tcl procedure and its solution.

## Description

The `bug.tcl` file contains a Tcl procedure `badproc` that takes two arguments (`a` and `b`).  The procedure attempts to divide `b` by `a`. If `a` is 0, this results in a division by zero error.

The solution demonstrates how to avoid this error using proper error handling and input validation.

## Solution

The `bugSolution.tcl` file provides a corrected version of the `badproc` procedure. It includes explicit error handling to catch cases where `a` is 0, preventing the runtime error.

This example highlights the importance of careful error handling in Tcl procedures to improve robustness and prevent unexpected crashes.