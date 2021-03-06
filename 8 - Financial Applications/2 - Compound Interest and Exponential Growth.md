Compound Interest and Exponential Growth
-------

### Definitions

* **Compound interest** is interest calculated at regular periods, called **compounding periods**. It is calculated on the current amount, as opposed to the original principal.
* An **interest rate per compounding period**, $i$, is the rate at which interest is charged, as a percent, per compounding period. It is a value between 0 and 1. 
* A **present value**, $PV$, is the principal invested or borrowed today to result in a given future amount, with given interest and time conditions.
* A **future value**, $FV$, is the amount that a principal invested or borrowed will grow to, with given interest and time conditions.

The following table shows a list of common methods of compounding.

| Frequency of Compounding | Number of Times Interest is Added During a Year |
| --- | --- |
| Annual | 1 (every year) 
| Semi-annual | 2 (every 6 months)|
| Quarterly | 4 (every 3 months) |
| Monthly | 12 (every month) |
| Bi-weekly | 26 (every 2 weeks) |
| Daily | 365 (every day) |


### Formulae

The amount after $n$ compounding periods can be calculated using $A = P(1 + i)^n$. To understand this formula, note that after each compounding period, the current amount increases by a rate of $i$, which is the same as multiplying it by $1 + i$. Therefore, after $n$ compounding periods, the amount is $P(1 + i)^n$. 

If we are solving for the principal, we can rearrange the formula above to get $FV = \frac{PV}{(1+i)^n}$. The present value is the principal, and the future value is the amount.

These formulae can be applied only when money is deposited or lent on only one occasion. If money is constantly being deposited or lent, we are not dealing with compound interest. 

If the rate of interest is not annual (i.e. per annum), we would use a slightly modified formula: $A = P(1 + \frac{i}{n})^{nt}$, where t is the amount of time that has passed.


### Growth of Compound Interest

Looking at the formula for compound interest, we can see that it is an exponential relation. This means that when you deposit money into an account using a compound interest plan and leave it, your money will grows in an exponential fashion.

Depending on how often the rate is applied, it might not always be growing. Often, the interest is applied after every year, which would resemble an **exponential step function** rather than an exponential function.

1. Describe an investment that could be represented by the function $f(x) = 500(1.05)^x$. 

2. Two investments are available, one at 6% compounded annually and the other at 6% compounded monthly. Investigate graphically the growth of each investment, and determine the interest earned from depositing $1000 in each investment for 10 years. 

TODO:
- make and describe connections between compound interest, geometric sequences, and exponential growth, through investigation with technology (e.g., use a spreadsheet to make compound interest calculations, determine finite differences in the amounts over time, and graph amount versus time) 
Sample problem: 
- solve problems, using a scientific calculator, that involve the calculation of the amount, A (also referred to as future value, FV), the principal, P (also referred to as present value, PV), or the interest rate per compounding period, i, using the compound interest formula in the form A = P(1 + i)n [or FV = PV(1 + i)n] 
- determine, through investigation using technology, the number of compounding periods, n, using the compound interest formula in the form A = P(1 + i)n [or FV = PV(1 + i)n]; describe strategies (e.g., guessing and checking; using the power of a power rule for exponents; using graphs) for calculating this number; and solve related problems 