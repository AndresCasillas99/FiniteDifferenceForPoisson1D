# FiniteDifferenceForPoisson1D
 We aim to approximate the solution of the one-dimensional Poisson problem in the unit square with zero boundary values using the method of Finite Differences. It includes plots to visualize approximate solutions for different partition values as well as computations for the maximum norm of the error term.  

Concretely, given 

$−∆u = f \hspace{0.5 cm}$ in $Ω = (0, 1)^{2}$ 

$u = 0 \hspace{0.5 cm}$ on $∂Ω$ 

and $n > 1$, we define a uniform grid of $Ω$ with $(n − 1)^{2}$ nodes $(x_{i}, y_{j}) = (\frac{i}{n}, {\frac{j}{n}})$ for $i,j = \{1,\dots,n-1\}$.

We then solve the lienar system of equations $Ax = b$ given by the finite difference method on this grid, and use it to plot approximate solutions against the analytic solution $u(x, y) = sin(2πx) sin(πy)$ as well as computations of $\max_{i,j = 1,\dots,n-1} |u_{i,j} - u(x_{i},y_{j})|$.



