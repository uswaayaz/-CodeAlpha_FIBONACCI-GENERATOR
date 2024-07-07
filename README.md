Here's a simpler explanation of the code:

Imagine climbing stairs:

The first step (F0) is at height 0.
The second step (F1) is at height 1.
To reach any other step (Fn), you add the heights of the two steps below it (Fn-1 and Fn-2).
The code mimics this:

Function (fib_recursion): This function acts like a helper to find the Fibonacci number.
Base Cases:
If you're at the first step (n == 0), your height is 0 (return 0).
If you're at the second step (n == 1), your height is 1 (return 1).
Recursive Case:
For any other step (n > 1), you don't know the height directly.
The code calls itself twice:
Once to find the height of the step below (n-1).
Once to find the height of the step before that (n-2).
It then adds these two heights to get your height (return fib_recursion(n-1) + fib_recursion(n-2)).
Input:
The code asks you for a number of steps (number).
Calling the function:
It calls the fib_recursion function with your chosen number of steps.
Output:
The code prints the Fibonacci number (height) for that step.
Key points:

Recursion: The function calls itself.
Base cases: These are stopping conditions that directly give the answer.
Recursive case: This is where the function breaks down the problem into smaller sub-problems using itself.

