# Stochastic Claims Reserving – Implementations

Illustrative Python implementations of two stochastic reserving methods for non-life insurance.

## Notebooks

**ICR_Model.ipynb** – Individual Claim Reserving (micro-level).  
Simulates each open claim forward through a 4-state event model (closure with/without payment, intermediate payment, empty event).  
Based on Chalnot, Gremillet & Miehe (2015) and Descamps (2017).

**Christofides_Verrall_Zhi.ipynb** – Log-incremental regression (aggregate). OLS on log-payments with full covariance accounting for the total reserve standard error, plus the Verrall–Li (1994) MLE extension for negative increments. Christofides (1990) 4x4 example.

## Scope

These are study implementations focused on the core methodology, not production reserving code. Tail factors, multi-line modelling, and some methodological extensions are out of scope.
