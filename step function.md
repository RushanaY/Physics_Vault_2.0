


In the case of a [[measurable map]] we have 
	- if $f(X)$ is a [[finite]] set 
	- if there are pairwise different $\alpha_i$ and [[disjunction|disjunct]] sets $A_i$ so that holds: $$f = \sum_{k=1}^n \alpha_k \mathbb{1}_{A_k}$$
	- if a function is only positive and in a [[measurable space]], then there is a sequence of $\mathcal{A}$- step functions with $f(x) = \lim_{n \to \infty}f_n(x)$ and $0 \leq f_n(x) \leq f_{n+1}f(x) \leq f(x)$ (monotocally increasing?) 


If we have a [[measure space]] and a defined step function $u :X \to [0, \infty]$  in  a [[sigma algebra]], the sets $A$ and $B$  being pairwise [[disjunction|disjoint]] and when put in a union back together the subsets creat the $C$ set back again.
- step function then defined as $$u = \sum_{k=1}^m \alpha_k \mathbb{1}_{A_k} = \sum^n_{l=1} \beta_1 \mathbb{1}_{B_1}$$
- then the property holds: $$\sum^m_{k =1} \alpha_k \mu(A_k) = \sum^n_{l=1}\beta_l \mu (B_l)$$
- ==what this bascially says is, that it doesn't matter how I split up my set in smaller parts, neither their union or the union of the "volume" = measure will be different, because we end up in the same set X back== 

Hopping from a measure, which is the length/volume, whatever, to the cooler definition, that will give the same length and volume gives the :
# [[integral]] 
$$\int_X u d \mu = \int_X u(x) d \mu(x)  := \sum_{k=1}^n \alpha_k \mu(A_k)$$ 