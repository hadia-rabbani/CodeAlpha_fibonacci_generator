# CodeAlpha_fibonacci_generator

Initialization: a and b are initialized to the first two terms of the Fibonacci sequence, 0 and 1 respectively.
Input Handling:
If num is 1, only the first term (0) is printed which is assigned to a.
If num is greater than 1, the first two terms (0 and 1) are printed initially.
Loop for Sequence Generation:
The loop starts from 2 and runs up to num - 1 (to generate num - 2 more terms since the first two terms are already printed).
In each iteration, the next term c is calculated as the sum of a and b.
a and b are updated to the next pair of preceding numbers like{(num-2)+(num-1)}.
The new term c is printed.
This way, the program correctly generates and prints the Fibonacci sequence up to the specified number of terms.
