# 14.1. [[sigma algebra]] and [[measurable map]]
## 14.1.1.  definition of [[sigma algebra]] 
"$\mathcal{A}$ is a  $\sigma$ - algebra on set X" => $(X, \mathcal{A})$ the short notation and is a [[measurable space]]  (a space X with a measure acting on it)

*collection of measurable subsets of a set X
those sets can be chosen to be together. We take only the ones that with the specific measure we want
properties about what kinds of sets should be inside*:
1. emtpy set and set itself $$\emptyset, X \in \mathcal{A}$$
2. complement of the set $$X/A \in \mathcal{A}$$
3. the union of all the subsets is also inthe algebra $$\bigcup_{n\in \mathbb{N}} A_n \in \mathcal{A}$$
## 14.1.2. remark 
$$\bigcap_{n \in \mathbb{N}} (X/V_n) = X/ (\bigcup_{n \in \mathbb{N}} V_n ) \in \mathcal{A}$$
$$\bigcap_{n\in \mathbb{N}} V_n = \bigcap_{n \in \mathbb{N}} (X/ (X/V_n)) = X/ (\bigcup_{n \in \mathbb{N}} (X / V_n) ) \in \mathcal{A}$$
*any intersection, no matter how is still part of the algebra*
## 14.1.3. examples 
for $X \neq \emptyset$ :
- $\mathcal{A}_1 =\{ \emptyset, X \}$ 
- $\mathcal{A}_2 = \mathcal{P} (X)$
- $\mathcal{A}_3 = \{ U \subset X: \text{U countable or X/U countble}\}$ 
are sigma algebras on X

### Proof: 
![[Kap.14 Integration 2026-02-25 14.21.14.excalidraw]]
## 14.1.4 examples 
If $\mathcal{A}$ is a [[sigma algebra]] onto X, then: 
- is $Y \subseteq X$, then $$\mathcal{A}_Y : = \{ Y \cap V: V \in \mathcal{A} \} \subseteq \mathcal{P} (Y)$$
- is $T :Z \to X$ a map, then $\{ T^{-1} (V) : V \in \mathcal{A} \} \subseteq \mathcal{P} (Z)$ is a sigma algebra on Z 
- is $f: X \to Y$ a map, then $$\mathcal{C} : = \{ V \subseteq Y :f^{-1} (V) \in \mathcal{A}\}$$a sigma algebra onto Y 
*what having a set, equipped with an algebra means for our actions. what will a subset do, what will the map do, where this special set is a domain or a range*
### Proof 
![[Kap.14 Integration 2026-02-25 14.30.43.excalidraw]]
x

## 14.2. [[measure]]

## 14.3. Integration of non linear function 
## 14.4. Integrable complex function 
## 14.5. Banach space

## 14.6. Integration of Banach functions 
