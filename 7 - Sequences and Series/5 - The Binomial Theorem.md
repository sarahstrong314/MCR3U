The Binomial Theorem
-------

Investigation: What patterns do we see when we expand $(x + y)^n$ for various natural numbers $n$?

The Binomial Theorem answers the following question: What is the expanded form of $(x + y)^n$ for any positive natural number $n$?


We can plug in various values of $n$ and expand the binomial to try to find a trend.

$(x + y)^1 = x + y$

$(x + y)^2 = x^2 + 2xy + y^2$

$(x + y)^3 = x^3 + 3x^2y + 3xy^2 + y^3$

$(x + y)^4 = x^4 + 4x^3y + 6x^2y^2 + 4xy^3 + y^4$

$(x + y)^5 = x^5 + 5x^4y + 10x^3y^2 + 10x^2y^3 + 5xy^4 + y^5$


If we look at the coefficients of each term in the expansion, we get the $n$th row of Pascal's Triangle.

The $k$th value in the $n$th row of Pascal's Triangle is denoted $\binom{n}{k}$, pronounced "$n$ choose $k$". This is covered in more detail in *Mathematics of Data Management*.

If we look at the degrees of $x$, it starts at $n$ and decreases by 1 each time.
If we look at the degrees of $y$, it starts at 0 and increases by 1 each time.

If we put this all together, we get the Binomial Theorem: $(x + y)^n = \sum_{i=0}^n{\binom{n}{i}x^{n-i}y^i}$, $n \ge 1$.


When we are interested in coeffecients of certain terms, we can use square brackets notation. When we put variables of specific degrees in square brackets in front of an expression, it represents the coeffiient of that term in the expression. If there is no such term, the coefficient is 0.

Example: What is $[xy](x + y)^2$?
$[xy](x + y)^2 = 2$.

Example: What is $[x^2y^3](x + y)^5$?
$[x^2y^3](x + y)^5 = 10$.

Use the Binomial Theoerm to expand the following functions and find $[x^2]f(x)$.

1. $f(x) = (2x + 1)^4$

2. $f(x) = (2 - 5y)^2$