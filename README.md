# Stochastic Volatility Inspired Parametrization

This project implements the Stochastic Volatility Inspired (SVI), Surface Stochastic Volatility Inspired (SSVI), 
and Extended Surface Stochastic Volatility Inspired (eSSVI) parameterization frameworks for arbitrage-free
implied volatility surface calibration.

The implementation includes parameter conversion between SVI formulations, 
calibration to observed market option data, enforcement of static arbitrage constraints, 
and robust optimization procedures for fitting implied volatility surfaces across strikes and maturities.

The eSSVI framework extends SSVI by allowing the correlation parameter to vary with maturity, 
improving calibration accuracy, particularly for short-dated maturities. 
The implementation follows the robust calibration methodology proposed in the literature.


## References
<a id="1">[1]</a> 
Gatheral, J. (2004). 
A Parsimonious Arbitrage-Free Implied Volatility Parameterization
with Application to the Valuation of Volatility Derivatives. 
Presented at the Global Derivatives & Risk Management Conference, Madrid, Spain.

<a id="2">[2]</a> 
Gatheral, J., Jacquier, A. (2014). 
Arbitrage-free SVI volatility surfaces. 
Quantitative Finance, 14(1), 59-71.

<a id="3">[3]</a> 
Corbetta, J., Cohort, P., Laachir, I., Martini, C. (2019). 
Robust calibration and arbitrage-free interpolation of SSVI slices. 
Decisions in Economics and Finance, 42, 665–677.
