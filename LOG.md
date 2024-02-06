# DAY 1 OF SE_DISCIPLINE CHALLENGE

What is Recursion?
-Recursion in programming is a technique where a function calls itself in order to solve a problem. Instead of solving the entire problem at once, the function breaks it down into smaller, more manageable sub-problems. These sub-problems are solved by calling the same function, and the results are combined to obtain the solution to the original problem.

Involvement of a Function Calling Itself:
-In a recursive function, the function calls itself during its execution. This self-referential behavior allows the function to solve a more complex problem by solving smaller instances of the same problem. Each recursive call contributes to breaking down the problem into simpler parts until a base case is reached.

Basic Idea of Breaking Down a Problem into Smaller Sub-Problems:
-The basic idea behind recursion is to break down a complex problem into smaller, more manageable sub-problems. Each recursive call works on a smaller instance of the original problem, making the problem-solving process more straightforward. The recursion continues until a base case is met, at which point the function stops calling itself and starts to combine the results obtained from the smaller sub-problems.

# Day 2 OF SE_DISCIPLINE CHALLENGE
FACTORIALS !!!!!!

I learnt how to do recursion with factorial basically a function calling itself until it gets to the base code 

n! = n * (n-1)!
int fact(int n){
  if (n >= 1) {return n * fact(n-1)}
  base code
  else {return 1} 
}

FIBONACCI SEQUENCE
I also learnt about the fibonacci sequeunce in which there is an arrays of number e.g 1, 1, 2, 3, 5, 8, 13....... where each number is gotten from the sum of the numbers before them

Fn = Fn-1 + Fn-2
this formula does not apply to the first two numbers

int fib(int n){
  if (n >= 3) {return fib(n-1) + fib(n-2)}
  else {return 1}
}
