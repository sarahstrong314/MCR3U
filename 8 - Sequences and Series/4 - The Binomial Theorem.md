The Binomial Theorem
-------

The Binomial Theorem answers the question what is the expansion of (x + y)^n?

We can plug in various values of n and expand the binomial to try to find a trend.

(x + y)^1 = x + y
(x + y)^2 = x^2 + 2xy + y^2
(x + y)^3 = x^3 + 3x^2y + 3xy^2 + y^3
(x + y)^4 = x^4 + 4x^3y + 6x^2y^2 + 4xy^3 + y^4
(x + y)^5 = x^5 + 5x^4y + 10x^3y^2 + 10x^y^3 + 5xy^4 + y^5

If we look at the coefficients of each term in the expansion, we get the nth row of Pascal's Triangle.
The kth value in the nth row of Pascal's Triangle is denoted \binom{n}{k}, pronounced n choose k

If we look at the degrees of x, it starts at n and decreases by 1 each time.
If we look at the degrees of y, it starts at 0 and increases by 1 each time.

If we put this all together, we get: (x + y)^n = \sum_{i=0}^n{\binom{n}{k}x^{n-i}y^i}
