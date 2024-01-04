# 100_theorems_58
Naproch Formalisation of Wiedijk 58 problems: "Formula for the Number of Combinations"

## Assignment (Temporary section)
In the paper, one should put the factorial ($n!$) and the binomial coefficients right after section 20 "Exponentiation".
Then the theorem itself (the number of $k$-element subsets of a set with n elements) is (n over k) should be behind section 28 "Number of Subsets of a Set".

One needs to define the factorial by a signature command.
The binomial coefficients are defined as $\frac{n!}{k! \cdot (n-k)!}$.

The crucial thing is the summation formula:
$${n +1 \choose k} = {n \choose k} + {n \choose k-1}$$

This will be nontrivial for Naproche, since the automated proving is not good with
arithmetic, fractions etc.

The summation formula corresponds to a similar argument for the "number of subsets";
there it was the simpler $2^{n+1} = 2^n + 2^n$.

After getting the mathematics to work, the files will have to be polished for
LaTeX, layout, explanatory text etc.

## Proof Layout
