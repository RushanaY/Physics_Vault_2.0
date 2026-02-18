==It is a set of subsets, that are stable under basic set operations, because it is already build out of the perfect and simple sets of the [[ring]]== 
$$\mathcal{F} : = \{V = \bigcup_{k=1}^N ]a_k, b_k] :N \in \mathbb{N} , a_k, b_k, \in \mathbb{R} , a_k \leq b\}$$
# Axioms
- $\exists ! \mu \text{ onto } \mathcal{F}, \forall a, b \in \mathbb{R} , a \leq b: \mu ( ]a,b]) = b-a$    -> there is only one [[content (inhalt)]] onto the ring of sets with this property 
	- => this content is then :
		- $\mu(B) \in [0, \infty[$ for every $B \in \mathcal{F}$ 
		- $\mu$ is a [[pre measure (prämaß)]] onto $\mathcal{F}$ 

- ther is exacly one [[Borel measure]] $\lambda: \mathcal{B} (\mathbb{R}) \to [0, \infty]$ with $\lambda ([a,b]) = b-a$ for $\forall a, b \in \mathbb{R} :a \leq b$ 

- the measure $\lambda$ has [[sigma continuity]], then for $\forall b \in \mathbb{R}$ we have $$\lambda (\{b\} = \lambda (\bigcap_{n \in \mathbb{N}} ] b - \frac{1}{n}, b]) = \lim_{n \to \infty} \lambda (]b - \frac{1}{n}, b]) = 0$$and from that also $$\lambda (]a, b]) - \lambda ([a,b[) = \lambda ([a, b]) = \lambda (] a, b [)$$
- 