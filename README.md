# limitcycles
Experimental implementations of algorithms based on the paper: An Algorithmic Approach to Limit Cycles of Nonlinear Differential Systems: The Averaging Method Revisited


The main functions implemented in "averaging-code.mw" are

# Normalize(P, Q, p, q, k)

-Computes the normal form of averaging up to k-th order in epsilon 

-- P and Q are polynomials in a considered planar differential system which has a center at the origin (from equation (3))

-- p and q are polynomials in the perturbations of a differential system (from equation (4))

-- k is the order in epsilon from the normal form of averaging (5) (usually called the averaging order).


# Averformula(k)

-Computes the formula of the k-th order integral function y_k(theta,z) (from equation (8) or equation (13))

-- k is the averaging order.


# AverFun(dr/d theta, k)

-Computes the symbolic expression of the k-th order averaged function f_k(z) (from equation (6))

-- dr/d theta is a normal form of averaging up to k-th order in epsilon obtained from the function Normalize(P, Q, p, q, k)

-- k is the averaging order.



# Support

The codes are partially supported by China Scholarship Council (#201806020128), and by NSF Grants #CCF-1423228 and #CCF-1564132.


