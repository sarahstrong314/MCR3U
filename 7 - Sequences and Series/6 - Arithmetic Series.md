Arithmetic Series
-------


Investigation: Find the sum of all the natural numbers from 1 to 100.


We want to find 1 + 2 + 3 + ... + 98 + 99 + 100.

Write it out twice, once forwards and once backwards, to get this:

1 + 2 + 3 + ... + 98 + 99 + 100

100 + 99 + 98 + ... + 3 + 2 + 1

If we add up both rows, we get twice the sum we want.

We can find that sum easily by adding each column rather than each row. 

Each column adds up to 101, and there are 100 rows so the total sum is 10100. However, we counted each number twice, so we have to divide by 2 to get 5050.

This gave us $S_100 = \frac{100(1+100)}{2}$.


The series of the first $n$ terms of an arithmetic sequence is $S_n = \frac{n(a+t_n)}{2}$.

Here is how the formula is derived.

Write out $S_n = a + (a + d) + (a + 2d) + ... + (a + (n-1)d)$ twice, once forwards and once backwards.

$S_n = a + (a + d) + (a + 2d) + ... + (a + (n-1)d)$
$S_n = (a + (n-1)d) + (a + (n-2)d) + (a + (n-3)d) + ... + a$

Each column in the RHS adds up to $2a + (n-1)d$. Since $t_n = a + (n-1)d$, each column $a + t_n$.
Since there are $n$ terms in the RHS, adding the two equations give $2S_n = n(a + t_n)$, which can be rearranged to get $S_n = \frac{n(a + t_n)}{2}$.



1. Find the sum of the first 100 terms of the following arithmetic series: $4 + 54 + 104 + 154 + 204 + ...$.

2. Find the sum of the following arithmetic series: $5 + 2 + (-1) + (-4) + (-7) + ... + (-279)$.

1. Given the following array built with grey and white connecting cubes, investigate how different ways of determining the total number of grey cubes can be used to evaluate the sum of the arithmetic series 1 + 2 + 3 + 4 + 5. Extend the series, use patterning to make generalizations for finding the sum, and test the generalizations for other arithmetic series. (TODO: graphic)

TODO:
- solve problems involving arithmetic and geometric sequences and series, including those arising from real-world applications 