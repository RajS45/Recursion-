# Recursion-

🔁What Is Recursion?

Recursion is a technique where a function calls itself to solve a problem. 
Each recursive call works on a smaller or simpler version of the original problem,
and the process continues until it reaches a base case—a condition where the function stops calling itself.


🧠 Core Components of Recursion
- Base Case: The simplest instance of the problem, which can be solved directly without further recursion.
- This prevents infinite loops.
- Recursive Case: The part where the function calls itself with modified parameters to move toward the base case.
- Termination Condition: Ensures that each recursive call progresses toward the base case.

🧩 Why Use Recursion?
- Divide and Conquer: Breaks problems into smaller subproblems (e.g., merge sort, quicksort).
- Tree Traversals: Inorder, preorder, postorder in binary trees.
- Backtracking: Solving puzzles like Sudoku, N-Queens.
- Dynamic Programming: When combined with memoization, recursion becomes a powerful tool for optimization.

 Example: Factorial Function .
 
int factorial(int n) {
    if (n == 0) return 1;         // Base case
    return n * factorial(n - 1);  // Recursive case
}

