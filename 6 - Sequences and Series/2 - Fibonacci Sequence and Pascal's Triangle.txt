Fibonacci Sequence and Pascal's Triangle
-------

### Fibonacci Sequence

The Fibonacci Sequence is this famous sequence: 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, ...

The first two terms are 1, then each term after that is the sum of its two previous terms.

The Fibonacci Sequence can be written as a recursive formula: t(1) = 1, t(2) = 1, t(n) = t(n-1) + t(n-2), n \ge 2.


### Pascal's Triangle

Pascal's Triangle contains many sequences that can be written as recursive formulae.

The second diagonal is 1, 2, 3, 4, 5, ..., which can be expressed as t_2(n)=n.
The third diagonal is 1, 3, 6, 10, 15, ..., which can be expressed as t_3(1) = 1, t_3(n) = t_3(n-1) + n, n \ge 2.
The fourth diagonal is 1, 4, 10, 20, 35, ..., which can be expressed as t_4(1)=1, t_4(n) = t_4(n-1) + t_3(n), n \ge 2.
