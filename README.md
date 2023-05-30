# Quanto Himalayan Option

Himalayan options are a form of path-dependent, exotic option on a basket of equity underliers, in which intermediate returns on selected equities enter the payoff, while the equities are subsequently removed from the basket. Himalayan option belongs to very exotic derivatives. Many exotic derivatives have barrier condition. 

For a set of d equities (stocks or equity indexes), let their respective prices at time t be Y1(t), . . . , Yd(t). Given a collection of fixing dates, t0, t1, . . . , td, let the equity returns Ri,j , for i = 1, . . . , d, j = 1, . . . , d be defined.

Moreover, let the integer-valued function k : {1, . . . , d} 7! {1, . . . , d} be defined so as to satisfy the following condition. k(i) is the index of the equity with the highest return, at the fixing date ti, among those equities, whose returns at the previous fixing dates were not the highest2. Given a strike level, K, the Himalayan option payoff is defined.

This definition is consistent with the one in the case of domestic equities, that is, in the absence of a quanto adjustment. In the quanto case, the effect of the change in the quanto adjustment resulting from a change in the volatility is ignored. 

With the exception of the theta, the hedge ratios are computed using Malliavin weights. The presence of the volatility calibration step requires an adjustment in the calculated Malliavin hedge ratios, according to the chain rule.

We employ the definitions of the respective hedge ratios, as stated in the section on the WM pricing method. With the exception of the theta, calculated through the
finite difference technique, all hedge ratios are computed using the Malliavin weight approach. Additional considerations arise from the impact of the calibration procedure on the sensitivity ratios, as describe in the next section.

Moreover, as can be seen from the test results below, the relative error in the gamma hedge ratios can be quite large. These quantities are generally very small, making the relative error a poor indicator of agreement. Moreover, it appears that the Monte Carlo sampling error is quite large for the gamma hedge ratio. 

For a large number of paths, this ratio should be approximately normally distributed with mean zero and unit variance, if the means in the two models are equal. We believe that this is a more meaningful way of comparing results whose Monte Carlo sampling error is large relative to the size of their expectation.

References:

https://derivatives.hcommons.org/currency-products/

https://osf.io/cg5x4/download

https://finpricing.com/lib/EqBarrier.html
