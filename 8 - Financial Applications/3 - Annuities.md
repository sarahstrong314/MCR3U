Annuities
-------

### Definitions

* **Regular payments**, $R$, are payments of equal value made at equal time periods.
* **Regular withdrawals**, $R$, are withdrawals of equal value at equal time periods.
* An **annuity** is a sum of money paid as a series of regular payments.
* An **ordinary annuity** is an annuity for which the payments are made at the end of each payment period.
* A **simple annuity** is an annuity for which the compounding and payment periods are the same.
* A **present value of an annuity**, $PV$, is the amount of money needed to finance a series of regular withdrawals
* A **future value**, $FV$, is the amount that an annuity will grow to, with given interest and time conditions.


### Formulae

The amount, $A$, of an ordinary annuity can be calculated using $A = \frac{R((1 + i)^n - 1)}{i}$, where $R$ is the regular payment, $i$ is the interest rate per compounding period, and $n$ is the number of compounding periods. 

If the first payment is made *before* the first compounding period, the formula we use is $A = \frac{R((1 + i)^n - 1)(1 + i)}{i}$.

The present value, $PV$, of an annuity can be calculated using $PV = \frac{R(1 - (1 + i)^{-n})}{i}$, where $R$ is the regular withdrawal. This is the amount you need to put into an account in order to afford making regular withdrawals after each compounding period for n compounding periods. 

These formulae can be applied only when annuities are involved. If money is deposited or lent on only one occasion, we are not dealing with annuities.

These formulae are noticeably more complex than the ones for simple and compound interest, and that is because the adding of more money to an account adds to the complexity.


### Understanding the Formulae

Here is a short explanation of how the formula $A = \frac{R((1 + i)^n - 1}{i}$ is derived. Let $A_n$ be the amount after $n$ compounding periods. We know that $A_n = A_(n - 1)(1 + i) + R$ since the total amount is increasing by $i$% each compounding period and we are adding $R$ to the total.

| $n$ | $A_n$ |
| --- | --- |
| 1 | $R$ |
| 2 | $A_1(1 + i) + R = R(1 + i) + R = R((1 + i) + 1) = R(2 + i)$ |
| 3 | $A_2(1 + i) + R = R(2 + i)(1 + i) + R = R((2 + i)(1 + i) + 1) = R((2 + 3i + i^2) + 1) = R(3 + 3i + i^2)$ |
| 4 | $A_3(1 + i) + R = R(3 + 3i + i^2)(1 + i) + R = R((3 + 3i + i^2)(1 + i) + 1) = ... = R(4 + 6i + 4i^2+ i^3)$ |

Notice the pattern in the polynomial that $R$ is multiplied by for each $A_n$. The coefficients are in the $n$th row of Pascal's triangle, with the final one omitted. This means that we can take $(1 + i)^n$, subtract the last term, which is always 1, then divide it all by $i$. This gives us the $\frac{(1 + i)^n - 1}{i}$ part of the formula. To complete this proof, we need to show that this pattern always continues, that is, $\frac{(1+i)^n - 1}{1 + i}(1 + i) + 1 = \frac{(1+i)^{n+1} - 1}{1 + i}$, which can be done after some tedious algebra. This explanation hopefully gives a good idea of why the formula works.

The formula $PV = \frac{R(1 - (1 + i)^{-n}{i}$ is derived quite similarly. It can be rearranged to get $PV = \frac{R(1+i)^n - 1}{i}\frac{1}{(1 + i)^n}$, which has the same right side as the formula above, with the exception of the factor of $\frac{1}{(1+i)^n}$.

Let $PV_n$ be the amount of money needed to finance n regular withdrawals. We know that $PV_n = (PV_(n-1) + R)(1 + i)^{-1}$ since we need enough to be able to withdraw $R$ after the interest rate of $i$ has been applied.

| $n$ | $PV_n$ |
| --- | --- |
| 1 | $R(1+i)^{-1}$ |
| 2 | $(PV_1 + R)(1 + i)^{-1} = (R(1 + i)^{-1} + R)(1 + i)^{-1} = R((1 + i)^{-1} + 1)(1 + i)^{-1} = R(\frac{1 + i + 1}{1 + i})(1 + i)^{-1} = \frac{R(2 + i)}{(1 + i)^2}$ |
| 3 | $(PV_2 + R)(1 + i)^{-1} = (\frac{R(2 + i)}{(1 + i)^2} + R)(1 + i)^{-1} = R(\frac{2 + i}{(1 + i)^2 + 1}(1 + i)^{-1} = ... = \frac{R(3 + 3i + i^2)}{(1 + i)^2}$ |
| 4 | $(PV_2 + R)(1 + i)^{-1} = (\frac{R(3 + 3i + i^2)}{(1 + i)^2} + R)(1 + i)^{-1} = R(\frac{3 + 3i + i^2}{(1 + i)^2 + 1}(1 + i)^{-1} = ... = \frac{R(4 + 6i + 4i^2 + i^3)}{(1 + i)^2}$ |

Comparing the two tables, we can see that in the second table each $PV_n$ has an additional factor of $\frac{1}{(1 + i)^n}$, but the values are otherwise identical. We can prove in a similar fashion as earlier how and why this formula works.