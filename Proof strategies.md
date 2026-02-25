1. [[Induktion]]
2. [[Contraposition]]: 
	- If p then q
	- if not p then not q
3. [[Proof by contradiction]] 
	- assume a statement is correct and show the contradiction 
4. [[proof by construction]] 
5. proof by exhaustion 
	- proving basically every case, even if there are infinetely many (done by computer)
6. closed chain interference (Ringschluss)
	- ust statement that ae pairwise equivalent $\phi_{n-1} \Rightarrow \phi_n$ and $\phi_n \Rightarrow \phi_1$ 
	- this is used in the transitivity condition of equivalence classes 
	- is way to make the proof faster. In essence it is still proving every case, but here you need only half of it 
7. nonconstructive proof 
	-  assumtion of a mathematical object with certain properties and then showing how to get it 
	- combinatorial proof 
		- used it cases I need to count something 
		- for example the definition of the k combinatorics  


# [[Quantifier]]s 

 to show $\forall x \in D: \phi (x)$ 
 
 Option 1: 
 1. Introduce a general $x$: *let $x \in D$* 
 2. show $\phi (x)$ 


to show $\exists x \in D: \phi (x)$ 
Option 1: 
1. select a conviniet element: *set* $x:=...$ so that $x \in D$ holds 
2. show $\phi (x)$ 

Option 2: 
- assume $\forall x \in D :\neg \phi (x)$ 
- show contradiction 
