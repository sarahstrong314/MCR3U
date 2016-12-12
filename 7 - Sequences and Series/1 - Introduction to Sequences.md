Introduction to Sequences
-------

A **sequence** is an ordered list of values, called **terms**.

Sequences are examples of **discrete functions**. So far we have been focusing on continuous funcitons.


### Function Notation

Sequences in function notation are often denoted with the $t$ instead of $f$.

The variable $n$ is conventionally used instead of $x$ to express that the independent variable, the term, is a natural number.

Sometimes, $t_n$ used instead of $t(n)$ to denote the $n$th term in a sequence.

Example: Write the sequence 1, 3, 7, 15, 31, ... in function notation. 
Each term is one less than the sequence 2, 4, 8, 16, 32, which is the sequences of powers of 2 starting at $2^1$. This tells us that the sequence 1, 3, 7, 15, 31, ... is $t(n) = 2^n - 1$ or $t_n = 2^n - 1$.


### Recursive Formulae

A recursive formula involves representing each term of a sequence with regard to the previous term.

To represent a sequence with recursive formula, we need the initial term(s) and an general expression for the other terms based on its previous term(s).

Example: Write the sequence 1, 3, 7, 15, 31, ... as a recursive formula.
The initial term is 1 and each term after that double the previus term plus 1. This tells us that the sequence 1, 3, 7, 15, 31, ... is $t(1) = 1$, $t(n) = 2t(n) + 1$, $n \ge 2$.

Just For Fun: Google "recursive".


### Fibonacci Sequence

The Fibonacci Sequence is this famous sequence: 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, ...

Investigation: What are the recursive patterns? How can we write it as a recursive formula

The first two terms are 1, then each term after that is the sum of its two previous terms.

The Fibonacci Sequence can be written as a recursive formula: $t(1) = 1$, $t(2) = 1$, $t(n) = t(n-1) + t(n-2)$, $n \ge 2$.



### Pascal's Triangle

Pascal's Triangle contains many sequences that can be written as recursive formulae.

The second diagonal is 1, 2, 3, 4, 5, ..., which can be expressed as $t_2(n) = n$.
The third diagonal is 1, 3, 6, 10, 15, ..., which can be expressed as $t_3(1) = 1$, $t_3(n) = t_3(n-1) + n$, $n \ge 2$.
The fourth diagonal is 1, 4, 10, 20, 35, ..., which can be expressed as $t_4(1) = 1$, $t_4(n) = t_4(n-1) + t_3(n)$, $n \ge 2$.

Each term in Pascal's Triangle can be denoted by $t_n,m$, where $n$ is the horizontal row number and $m$ is the diagonal row number. The very first 1 is considered to be $t_0,0$, and is sometimes even excluded from the triangle.

Example: What is $t_4,3$ of Pascal's triangle? 
The 4th row is 1, 4, 6, 4, 1, so $t_4,3 = 6. 


Write each of the following sequences either in function notation or as a recursive formula.

1. 0, 2, 6, 12, 20, 30, 42, ... 

2. 1, 4, 27, 1024, 3125, ...

3. 1, 1, 1, 3, 5, 9, 17, 31, ...