# Stochastic Claims Reserving – Implementations

Python implementations of two stochastic reserving methods for non-life insurance, covering both micro-level (individual claim) and aggregate modelling approaches.

## Notebooks

**ICR_Model.ipynb** – Individual Claim Reserving (micro-level).  
Simulates open claims using a 4-state event model (closure with/without payment, intermediate payment, no-event), with stochastic severity modelling.  
Based on Chalnot, Gremillet & Miehe (2015) and Descamps (2017).

**Christofides_Verrall_Zhi.ipynb** – Aggregate reserving via log-incremental regression.  
Implements OLS on log-payments with full covariance estimation of reserve uncertainty, including the Verrall–Li (1994) MLE extension for negative increments.  
Based on Christofides (1990).

## Scope

These are study implementations focused on core reserving methodology rather than production systems. Tail factors, multi-line modelling, and additional extensions are not included.
