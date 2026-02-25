# Definitions
"$\mathcal{A}$ is a  $\sigma$ - algebra on set X" => $(X, \mathcal{A})$ the short notation and is a [[measurable space]]  (a space X with a measure acting on it)

*collection of measurable subsets of a set X
those sets can be chosen to be together. We take only the ones that with the specific measure we want
properties about what kinds of sets should be inside*:
1. emtpy set and set itself $$\emptyset, X \in \mathcal{A}$$
2. complement of the set $$X/A \in \mathcal{A}$$
3. the union of all the subsets is also inthe algebra $$\bigcup_{n\in \mathbb{N}} A_n \in \mathcal{A}$$




# Application:
- Define a sigma algebtra onto a set X
	- define multiple algebras and take an intersection of them 

Erzeugte albegra: 
$$\sigma ({\mathcal{E}}) : = \bigcap_{\mathcal{E} \subseteq \mathcal{A} \subseteq \mathcal{P}(X)} \mathcal{A}$$
define the smallest possible algebra of subset M of the set X
	- the set X has to be a [[topology]] $(X, \mathcal{O})$    and this is then a [[Borel algebra]]  $$\mathcal{B} = \mathcal{B} (X) := \sigma (\mathcal{O})$$

A [[family]] of sigma albegra onto X is also a sigma albegra on the same set X $$\bigcap_{i \in I} \mathcal{A_i} = \{V \subseteq X: V \in \mathcal{A}_i \text{ for all } i \in I\}$$
-> proof goes the same, as just showing that something is an algebra. Important: we go from the assumtion that the full $\mathcal{A}$ is already proven to be an algebra onto X and we can therefore use all their properties


In order to make an algebra using the easier way, we use the [[Caratheodory]] method, where we first define the [[pre measure (prämaß)]], then a [[outer measure (äußeres Maß)]] and then chooose only those sets that are "god" and we end up with the perfect [[sigma algebra]]

# To know by heart: 
$$\bigcap_{n\in \mathbb{N}} (X/V_n) = X/ (\bigcup_{n\in \mathbb{N}} V_n) \in \mathcal{A}$$*is that a type of [[de Morgan's rule]] rule?* $$\bigcap_{n \in \mathbb{N}} V_n = \bigcup_{n \in \mathbb{N}} (X/ (X/V_n)) = X/ (\bigcup_{n \in \mathbb{N}} (X/V_n)) \in \mathcal{A}$$
# Proof strategies 
how to show that something is a algebra onto set X
-> use the three properties and show them. Important is to show that the set  remains in properties in all three cases. It is wrong if the empty set is countable, but then the union is not. If the defining property of the sets we choose is that they are countable, then all the properties of the algebra have to  be possible and also have to be also countable in every case. Be sure to show all the cases. 








# example 
- smalles possible algebra: empty set and set itself 
- bigges possible algebra: power set
![[sigma algebra 2025-12-03 12.03.18.excalidraw]]
![[sigma algebra 2025-12-03 12.10.14.excalidraw]]