# real-options-least-squares-monte-carlo-python
Valuing Real Options with Least Squares Monte Carlo in Python

Simple Real Option Value using Least Squares Monte Carlo (LSMC)

Smith (2005) describes a straighforward procedure to value a real option
using Longstaff and Schwartz (2001) LSMC method and gives a simple
example (pp. 88-89). This code performs the steps discussed by Smith (2005) 
but with a different example.

Setup: Mine Co. is evaluating a widget mine with a 10 year life. Mine Co.
is considering a proposal by another company (Mine Ltd.) wherein Mine Co. 
would have the option to sell its interest to Mine Ltd. at the end of year 5. 
It can only excerise this option at the end of year 5 and not before or after. 
The price of widgets folllow a GBM process, and the mine's operating cost 
follows a mean-reverting process.

Question: What is the value of this option? The goal of this code is to
estimate this option value.

References:
Smith, James E. "Alternative Approaches for Solving Real-Options Problems: 
    (Comment on Brandão et al. 2005)." Decision Analysis 2, no. 2 (2005): 89-102.
    
Longstaff, Francis A., and Eduardo S. Schwartz. "Valuing American options by 
    simulation: a simple least-squares approach." The review of financial 
    studies 14, no. 1 (2001): 113-147.
