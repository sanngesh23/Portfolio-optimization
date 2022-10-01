# Portfolio-optimization

The modern portfolio theory (MPT) is a practical method for selecting investments in order to maximize their overall returns within an acceptable level of risk.

The modern portfolio theory argues that any given investment's risk and return characteristics should not be viewed alone but should be evaluated by how it affects the overall portfolio's risk and return. That is, an investor can construct a portfolio of multiple assets that will result in greater returns without a higher level of risk.

## Sharpe Ratio 
The Sharpe ratio compares the return of an investment with its risk. It's a mathematical expression of the insight that excess returns over a period of time may signify more volatility and risk, rather than investing skill.


$$ SR(w) = \frac{R(w)-R_f}{\sigma(w)} $$

$$ w = [ w_1  w_2  w_3  w_4  ] $$

$$ \sum_{k=0}^4 w_k= 1 $$

$$ R(w) = w^T log(r) $$

$$ \sigma(w) = \sqrt{w^T {\sum w} } $$

$$ SR(w) = \frac{w^T log(r)}{\sqrt{w^T \sum w}} $$

## Efficient Markowitz Frontier  
In modern portfolio theory, the efficient frontier is an investment portfolio which occupies the "efficient" parts of the risk–return spectrum. Formally, it is the set of portfolios which satisfy the condition that no other portfolio exists with a higher expected return but with the same standard deviation of return.

$$ minimize \ w: w^T\sum w $$

$$ subject \to p^{-T} w >= r_{min} $$

$$ w >=0 $$

$$ 1^T w = 1 $$

$$ minimize\ w: -SR(w) $$

$$ subject\ to\ 0\leq w_i\geq 1, i=1....4 $$
