Domains and Ranges of Functions
-------

### Set Notation

Some well-known sets of numbers have names, but they can also be written using set notation.

We can write sets by explicitly writing out each element, and use ellipses (the "...") to mean "you get the idea" if the trend is clear. Sometimes we cannot explicitly write out the elements in a set. If this is the case, we can describe a pattern. We write out a general expression for the elements, then a colon or a pipe, then the condition of the constants in the expression.

Here are some common sets of numbers that have names.

| Name| Description | Set Notation |
| --- | --- | --- |
| $\mathbb{N}$ | The set of natural numbers | ${1, 2, 3, 4, ...}$ |
| $\mathbb{Z}$ | The set of integers | ${..., -2, -1, 0, 1, 2, ...}$ |
| $\mathbb{Q}$ | The set of rational numbers | ${\frac{a}{b} : a,b \in \mathbb{Z}, b \ne 0}$ |
| $\mathbb{R}$ | The set of real numbers | N/A |

The letter Z in the set of integers comes from the German word for numbers, *zahlen*

The set of rational numbers would be read as "$a$ over $b$ where $a$ and $b$ are in the set of integers and $b$ is not equal to 0".  Another way to think of this example is that $\mathbb{Q}$ contains all fractions in the form $\frac{a}{b}$ where $a$ and $b$ are both integers and $b$ is not 0. The letter Q comes from the word *quotient*.

The set of real numbers cannot easily be expressed in set notation with what we have learned so far.

To denote whether an element is contained in a set, we use the symbol $\in$, often pronounced "in". It is neither an "e" nor the Greek letter "epsilon". We can also use $\notin$ to denote that an element is not contained in a set.

Here are some examples of the use of $\in$ and $\notin$: $1 \in \mathbb{N}$, $1 \in \mathbb{Z}$, $-1 \notin \mathbb{N}$, $0.5 \notin \mathbb{Z}$.

$\mathbb{N}$, $\mathbb{Z}$, $\mathbb{Q}$, and $\mathbb{R}$ are all **infinite sets** since they have infinitely many elements. Sets that have finitely many elements are called **finite sets**.



### Domain and Range

The **domain** of a function is the set of values that the independent variable can be.
The **range** of a function is the set of values that the dependent variable can be.

Here are some examples of domains and ranges of common functions. To exclude certain values in a set, we can use a colon (:) or pipe (|) to separate the set and the restriction. The colon or pipe is often read as "such as".

| Domain | Range |
| --- | --- | --- |
| $f(x) = x$ | $\mathbb{R}$ | $\mathbb{R}$ |
| $f(x) = x^2$ | $\mathbb{R}$ | $\mathbb{R}$ |
| $f(x) = \sqrt{x}$ | ${\mathbb{R}: x \le 0}$ | ${\mathbb{R}: x \le 0}$ |
| $(x) = \frac{1}{x}$ | ${\mathbb{R}: x \ne 0}$ | ${\mathbb{R}: $x \ne 0}$ |
| $(x) = \abs{x}$ | $\mathbb{R}$ | ${\mathbb{R}: $x \ge 0}$ |


What are the domain and range of each of the following functions?

1. $f(x) = x^2 + 2$

2. $f(x) = -x^2 - 1$

3. $f(x) = \frac{1}{x - 3}$


When functions are used to model real-life data, sometimes there may be other restrictions. For example, if time is the independent variable, the domain might be ${$\mathbb{R}$: $x \le 0$}$, since negative time does not always make sense.


1. A quadratic function represents the relationship between the height of a ball and the time elapsed since the ball was thrown. What physical factors will restrict the domain and range of the quadratic function? 


### Interval Notation

We can also use what is called **interval notation** to express the domain and range of a function. It uses two points: the starting point and the ending point, brackets around them that determine whether the points are included or excluded from the interval.

| Interval Notation | Inequality Notation |
| --- | --- |
| $[a,b]$ | $a \le x \le b$ |
| $(a,b)$ | $a < x < b$ |
| $[a,b)$ | $a \le x < b$ |
| $(a,b]$ | $a < x \le b$ |

If there is no bound in one or both of the directions, we can use $−\infty$ for $a$ or $\infty$ for $b$. $(0, \infty)$ is the set of positive real numbers, and $(-\infty, \infty)$ is the set of all real numbers. To denote that a given value is in an interval, we can still use the $\in$ symbol. We can write expressions such as $4 \in (0, 5)$.

Express the following in interval noration.

1. $3 < x \le 8$

2. $ x < 4$

3. $ -2 \le x$


### Continuous and Discrete Functions

A **continuous function** is a function whose domain is one interval of real numbers. All continuous functions can be graphed and traced without lifting up the pencil.

A **discrete function** is a function that can be written explicitly as a finite number of ordered pairs. All discrete functions can be graphed by plotting a point for each coordinate.

Some types of discrete functions are not often graphed. The Fibonacci Sequence is an example of a discrete function, and it is often simply written as a list of values: $1, 1, 2, 3, 5, 8, 13, 21, 34, 55, ...$. In this case, the independent variable is the term number, and the dependent variable is the value.

Not all functions are either continuous or discrete.