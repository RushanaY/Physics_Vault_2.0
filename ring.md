==probably this ring allows us to easily add and multiply set, just like we do with integers. While the whole thing looks like ususal behaviour with integers, we actually still keep the structure form the sets, but get the ability to do integer stuff with it==


It is a [[Set]] $\mathcal{R} \subseteq \mathcal{P}(X)$, when 
1. $\emptyset \in \mathcal{R}$ 
2. $\forall A,B \in \mathcal{R}, B \subseteq A :A/B \in \mathcal{R}$ 
3. $A,B \in \mathcal{R}$ is $A \cup B \in \mathcal{R}$ 

If $X \in \mathcal{R}$ then the ring is the [[Mengenalgebra (field of sets)]] -> if there is a defined set inside the ring, then it is 


==this is the content of the ring, which is bascially the volume or the size of the ring. Remember how the [[measure]] is the volume or length of a set, so this is the same thing over another structre==


# [[pre measure (prämaß)]] 
==this is the easier version of a measure, because the range of this function doesn't have to be a sigma algebra necceraly -> **choose the easy sets**==
The map $\mu: \mathcal{R} \to [0, \infty]$ with 
- $\mu (\emptyset) = 0$     
- for a finite number of pariwise [[disjunction|disjount]] sets in the ring we have the [[content (inhalt)]] defined a: 
$$\mu (\bigcup_{k =1}^{N} A_k) = \sum_{k=1}^N \mu (A_k)$$
# [[outer measure (äußeres Maß)]] 
==this measure is a "view from above", where we take a bit more, so we don't miss anything -> this is why only subadditivity, not the strict additivity==
It is a function $\mu^* : \mathcal{P} (X) \to [0, \infty]$ with the properties: 
- $\mu^* (\emptyset) = 0$ 
- $\forall A \subseteq B \subseteq X :\mu^*(A) \leq \mu^* (B)$ 
- for all [[sequence]]s $(A_n)_{n \in \mathbb{N}} \in \mathcal{P}(X)$ we have the [[sigma subadditivity]]   


Standard method - [[Caratheodory]]  