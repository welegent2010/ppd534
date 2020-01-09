# Assignment 2: Coding Logic

Due Wed 12 Feb by 23:59 via Blackboard submission.

1. You will create your first complete Jupyter notebook in order to work with loops, conditionals, iteration, and functions. Review *Think Python* section 4.8 to develop a plan and section 6.2 on incremental development. Also review the code in the notebook from this class session.
2. You will write four functions to work with prime numbers. A prime number is any whole number greater than 1 that has no positive divisors besides 1 and itself. So, a prime number a) must be an integer, b) must be greater than 1, and c) must be divisible only by 1 and itself.
   1. Write a function `is_prime(n)` that accepts an argument n and returns boolean True if n is a prime number and boolean False if n is not prime. For example, `is_prime(11)` should return True and `is_prime(12)` should return False.
   2. Write a function `print_primes(n)` that accepts an argument n and prints all the prime numbers between 0 and n (inclusive). This function should call the `is_prime` function you developed earlier. For example, `print_primes(13)` should print out: 2 3 5 7 11 13
   3. Write a function `count_primes(n)` that accepts an argument n and returns an integer count of how many prime numbers there are between 0 and n (inclusive). This function should also call the `is_prime` function you developed earlier. For example, `count_primes(19)` should return 8, because there are eight prime numbers between 0 and 19.
   4. Write a function `first_primes(n)` that accepts an argument n and returns a Python list containing the first n prime numbers. (Hint: use a while loop and append each prime you find to a list.) This function should also call the `is_prime` function you developed earlier. For example, `first_primes(5)` should return the first five prime numbers as a list: `[2, 3, 5, 7, 11]`
3. Create a new, clean notebook to contain your work. The first cell in your notebook should be a markdown cell containing a plain-English narrative of the a) logic you will need to code and b) how your development process corresponds to *Think Python* sections 4.8 and 6.2. Use this narrative to think through how you will tackle each function. Each of the four functions should be in its own notebook cell. At the end of each of these cells, call the function by passing in a test value to demonstrate that it is working properly.

At the end of the notebook, include a markdown cell that identifies each group member and describes their contribution to this assignment (one sentence each).

Make sure your entire notebook runs properly and without any errors. Click Kernel > Restart > Clear all outputs and restart. This clears your memory and re-initializes your notebook. Then click Cell > Run all and make sure everything behaves properly. Give your notebook a meaningful filename like `team_number-assignment2.ipynb`. Submit your notebook file on Blackboard by its due date. Before submitting, confirm the following to the best of your abilities: does your code fully run? Does it do what it's supposed to do the way it's supposed to do it? Is it well-commented and documented? Is your code clear, straightforward, and reasonably efficient?