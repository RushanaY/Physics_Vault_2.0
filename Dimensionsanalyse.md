= to check the correctness of a physical fomular

| Unit         | Name      | Dimensionalformular          |
| ------------ | --------- | ---------------------------- |
| kg           | mass      | M                            |
| l, b, r, ... | lenght    | L                            |
| t            | time      | T                            |
| f            | frequency | $T^{-1}$                     |
| ...          | ...       | ...                          |
| J            | Energy    | $M \cdot L^2 \cdot T^{-2}$   |
| P            | power     | $M \cdot L^{2} \cdot T^{-3}$ |
| F            | force     | $M \cdot L \cdot T^{-1}$     |



- **check dimensions**: 
$$s = v \cdot t = [L][T]^{-1} \cdot [T] = [L]$$
	is correct, beacause we want to get lengh and we get that 

- **create formular**
	- Ansatz: $t \propto h^a \cdot g^b$ 
	- we know: 
		- $h$ in $[L]$
		- $g$ in $[L][T]^{-2}$ 
		-> we want t in $[T]$ in form: $[T] = ([L])^a \cdot ([L][T^{-2}])^b = [L]^{a+b} \cdot [T]^{-2b}$ 
	- compare dimensions
		$$[T]^1 = [T]^{-2b} \to b = -\frac{1}{2}$$
		$$0 = a+b \to a = -b = \frac{1}{2}$$
		=>$t \propto \sqrt{\frac{h}{g}}$  