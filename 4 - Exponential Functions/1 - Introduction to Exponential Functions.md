Introduction to Exponential Functions
-------

### Examples of Exponential Functions

Here are examples of **exponential functions**.

$f(x) = 2^x$

$f(x) = -3^x - 8$

$f(x) = 0.5^{x - 5}$

$f(x) = 2*4^{x + 3} + 3$

All exponential functions have the independent variable occurring only once in an exponent.


### Properties of Exponential Functions

The **base** of an exponential function is the base to the exponent the variable is in. 

For example, the base of $2^x$ is 2, and the base of $-3^x - 8$ is 3. In this course, we will be dealing with only positive bases.

All exponential functions have a **horizontal asymptote**, which is a horizontal line that the function approaches, but does not cross. This asymptote exists because $0 = b^x$ does not have a solution for any value of $b$.

All exponential functions also have only one $y$-intercept.


### Solving Exponential Equations

We know how to evaluate expressions with exponents, but what about solving for variables in the exponent? For example, how would we find the value of $x$ in $256 = 2^x$? 

If $x$ happens to be an integer or a rational number, we can simply write both sides using the same base. We can solve the previous example by getting a common base of 2. We continuously dividing 256 by 2 until we get 1, and counting how many times it takes. It took 8 times, so $256 = 2^8$. Then we can write $2^8 = 2^x$, which means $x = 8$.

Here is another example: $3 = 81^x$. This time, we can get a common base of 3. We divide 81 by 3 over and over again until we get 1, and counting how many times it takes. It took 4 times, so $81 = 3^4$. Then we have $3 = (3^4)^x = 3^{4x}$. We equate the exponents to get $1 = 4x$, so $x = \frac{1}{4}$.

Sometimes we have to change both bases to determine the value of x. For example, we in $8^x = 32$, we cannot multiply 8 by itself over and over again to get 32. However, we can rewrite $8^x$ as $2^{3x}$ since they are both equivalent. After determining that $2^5 = 32$, we get $3x = 5$ and thus $x = \frac{5}{3}$.

If we cannot get a common base, we can use the **logarithm** function to calculate the exact amount. To solve for $a = b^x$, we calculate $x = \frac{log(a)}{log(b)}$ using the log button on a calculator. The logarithm function is the inverse of the exponential function, and will be covered in more detail in *Advanced Functions*.


Solve for $x$ without using logarithms.

1. $7^x = 2401$

2. $5 = 5^x$

3. $9^x = 27$

### Power Table

You may find this following table useful. The initial column represents bases and the initial row represents powers.

|   | **2** | **3** | **4** | **5** |
| --- | --- | --- | --- | --- |
| **2** | 4 | 8 | 16 | 32 |
| **3** | 9 | 27 | 81 | 273 |
| **4** | 16 | 64 | 256 | 1024 |
| **5** | 25 | 125 | 625 | 3125 |


### Real-life Exponential Growth and Decay

* Population growth
* Compound interest
* Chemical reactions
* Radioactivity


### Inverses of Exponential Functions

The inverse of an exponential function is called a **logarithmic function**. The inverse of an exponential function $f(x)= a^x$ is $f^{-1}(x) = log_2x$. Logarithmic functions are also covered in *Advanced Functions*.
