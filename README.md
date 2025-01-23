# Unhandled Exception in TypeScript Arithmetic Operations

This repository demonstrates a common error in TypeScript: failing to handle potential runtime errors, specifically in this case, division by zero. The `bug.ts` file shows the faulty code, while `bugSolution.ts` provides a corrected version with proper error handling.

## Problem

The original code lacks proper exception handling within the `divide` function.  If a user attempts to divide by zero, the function throws an error that is not caught, resulting in the program crashing.

## Solution

The solution involves using a `try...catch` block to gracefully handle the potential `Error` thrown by the `divide` function. This prevents the program from terminating abruptly and allows for a more robust user experience.