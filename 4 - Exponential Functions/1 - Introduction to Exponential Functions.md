Introduction to Exponential Functions
-------

### Examples of Exponential Functions

Here are examples of **exponential functions**.

$f(x) = 2^x$

$f(x) = -3^x - 8$

$f(x) = 0.5^{x - 5}$

$f(x) = 2*4^{x + 3} + 3$

All exponential functions have the independent variable occurring only once in an exponent.


Investigation: Using Desmos, graph the exponential functiosn above, and verify that they are all indeed functions. 

Investigation: How to exponential functions differ from linear and quadratic functions in terms of their equations, their finite differences in tables of values, and their graphs?


### Properties of Exponential Functions

The **base** of an exponential function is the base to the exponent the variable is in. 

Example: What is the base of $2^x$ and $-3^x - 8$?
The base of $2^x$ is 2 and the base $-3^x - 8$ (which is equivalent to $-(3)^x - 8$ ) is 3. 

In this course, we will be dealing with only positive bases.

All exponential functions have a **horizontal asymptote**, which is a horizontal line that the function approaches, but does not cross. This asymptote exists because $0 = b^x$ does not have a solution for any value of $b$.

All exponential functions also have only one $y$-intercept.

All exponential functions are either increasing or decreasing or increasing functions, meaning it is either continuously growing (increasing) or continuously decaying (decreasing).


Give a two possible equations for each of the following exponential functions, given its description. 

1. The base is 2, the y-intercept is $(0, 4)$, and the horizontal asymptote is $f(x) = 3$.

2. The base is 3, the y-intercept is $(0, 0)$, and the horizontal asymptote is $f(x) = -2$.



### Solving Exponential Equations

We know how to evaluate expressions with exponents, but solving for variables in the exponent is a different process. If the value of the variable happens to be an integer or a rational number, we can simply write both sides using the same base, often the smallest among the choices.

Example: Find the value of $x$ in $256 = 2^x$.

We can get a common base of 2 on both sides. If we continuously dividing 256 by 2, it takes 8 times to reach 1. This tells us that $256 = 2^8$, which means $x = 8$.

Example: Find the value of $x$ in $3 = 81^x$.

We can get a common base of 3 on both sides. If we continuously divide 81 by 3, it takes 4 times to reach 1. This tells us that $81 = 3^4$, so we can rewrite $81^x$ as $3^{4x}$. By equating the exponents, we get $1 = 4x$, giving $x = \frac{1}{4}$.

Sometimes we have to change both bases to determine the value of x. 

Example: Find the value of $x$ in $8^x = 32$.

We cannot get a common base of 8 since 32 is not a power of 8. However, since 8 and 32 are both powers of 2, we can rewrite $8^x$ as $2^{3x}$ and 32 as $2^5$. By equating the exponents, we get $3x = 5$, giving $x = \frac{5}{3}$.



### Power Table

Solving for exponents often requires one to recognize what base to use, so it should be helpful to study the following power table.

The initial column represents bases and the initial row represents powers.

|   | **2** | **3** | **4** | **5** |
| --- | --- | --- | --- | --- |
| **2** | 4 | 8 | 16 | 32 |
| **3** | 9 | 27 | 81 | 273 |
| **4** | 16 | 64 | 256 | 1024 |
| **5** | 25 | 125 | 625 | 3125 |


Solve for $x$.

1. $7^x = 2401$

2. $5 = 5^x$

3. $9^x = 27$

### Logarithms

If we cannot get a common base, we can use the **logarithm** function to calculate the exact value of $x$. To solve for $a = b^x$, we calculate $x = \frac{log(a)}{log(b)}$ using the log button on a calculator. The logarithm function is the inverse of the exponential function, and will be covered in more detail in *Advanced Functions*.

### Real-life Exponential Growth and Decay

* Population growth
* Compound interest
* Chemical reactions
* Radioactivity


### Inverses of Exponential Functions

The inverse of an exponential function is called a **logarithmic function**. The inverse of an exponential function $f(x)= a^x$ is $f^{-1}(x) = log_2x$. Logarithmic functions are also covered in *Advanced Functions*.