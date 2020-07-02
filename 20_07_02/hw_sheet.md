# Homework 20_06_29
## JMP TechLive, C Programming

**PS**: You should provide a test program which include the `main` function to test your functions, with the possibility of user input.

### Functions

Write the following functions.

- ```int is_leap(int year)```

    It checks if a given year is leap or not, it returns `1` if it's leap and `0` if not.

    Info: *A leap year is exactly divisible by 4 except for century years (years ending with 00). The century year is a leap year only if it is perfectly divisible by 400*.

- `int seq_arith(int u0, int d, int n)`

    It calculates the value of **n-th** element of a geometric sequence, where **u0** is the initial element and **d** is thte common difference.

    *DON'T use the simplified formula, unless for testing.*

- `int seq_geometric(int u0, int r, int n)`

    It calculates the value of **n-th** element of a geometric sequence, where **u0** is the initial element and **r** is the common ratio.

    *DON'T use the simplified formula, unless for testing.*

- `int fact(int n)`

    It caclulates the factorial number of **n**.

- `int print_fibonacci(int n)`

    It displays the Fibonacci sequence of first n numbers.

    *The Fibonacci sequence is a sequence where the next term is the sum of the previous two terms. The first two terms of the Fibonacci sequence are `0` followed by `1`.*

    *DON'T use the simplified formula, unless for testing.*

- `int hcf(int a, int b)`

    It calculates **HCF** (**PGCD**) of two integers (for both positive and negative integers).

    *DON'T use the simplified formula, unless for testing.*

- `int lcm(int a, int b)`

    It calculate the **LCM** (*Lowest common multiple*) of two numbers.

    *DON'T use the simplified formula, unless for testing.*

- `int n_digits(long long int n)`

    It count the number of digits in an integer.

- `long long int n_reverse(long long int n)`

    It reverse the number `n`, ie: `20394` become `49302`.

- `int n_palindrome(long long int n)`

    It checks whether the number `n` is a palindrome or not. it returns `1` if it's palindrom and `0` otherwise. ie: `27572` is palindrome.

- `int is_armstrong(int n)`

    It checks whether an integer `n` is an Armstrong number or not. it returns `1` if it's Armstrong number and `0` otherwise.
