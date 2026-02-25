big connection for [[T1 Muchanov]]

homogenity of time -> conservation of energy
homogenity of space -> conservation of momentum 


from lagrandge with position and velocity we go to hamilton with position and momentum
$$p = \frac{\partial L}{\partial \dot q}$$
use [[Legendre transform]]
$$d f(x) = \frac{\partial f}{\partial x} dx$$
=> $$df = p dx$$
define: $g = px -f$
with total differential: $dg = pdx + xdp - pdx = xdp$ 
=> $\frac{df}{dx} = p$ and $\frac{dg}{dp} = x$ , $g = px -f$ 
applied: 
- define usind the g term: $H = p \dot q -L$ because $\frac{\partial L}{\partial \dot q} = p$ 
	- using the similarities: $$\frac{\partial H}{\partial p }= \dot q$$
	- Reason: 
		- take total differentials of Lagrandge and Hamiltonian ($H = p \dot q - L$)  $$dH = \dot q dp + p d \dot q - \frac{\partial L }{\partial q} dq - \frac{\partial L }{\partial q} d \dot q = \dot q dp - \frac{\partial L}{\partial q} dq$$
			- a very specific equatin. but the general Hamiltonial needs only two variables 
		- actual total differential of H can be matched one to one to the equation we have gotten. Just because the thing is linear 
		- thereofre we have the **Hamiltons equations**: $$\frac{\partial H}{\partial p} = \dot q$$
			- important: it has to be a partial differential, because Hamiltonian is dependand also on L and it should not be forgotten. Ecslepially  because we got this termn by one to one matching of two linear terms. 
		- $$\frac{\partial H}{\partial q} = -\frac{\partial L}{\partial q} = - \dot p$$
			- because $\frac{\partial L}{\partial q} = \frac{d}{dt} \frac{\partial L}{\partial \dot q} = \frac{d}{dt}p = \dot p$. 
			- where the Euler Lagrandge equation was used 



**Poisson brackets** $[H,f]$
taking the total time derivative: $$\frac{df}{dt} = \frac{\partial f}{\partial t} + \frac{\partial f}{\partial q} \frac{dq}{dt} + \frac{\partial f}{\partial p} \frac{dp}{dt} = \frac{\partial f}{\partial t} + [\frac{\partial f}{\partial q} \frac{\partial H}{\partial p} - \frac{\partial f}{\partial p} \frac{\partial H}{\partial q}] = \frac{\partial f}{\partial t} - [H,f]$$ 

**Eulerian angles**
-> show where object is in relation to the three axies 
	-> angles go only between axis 
basically it's the expressing of carteisan coordinates in spherical ones 
or also look like Christoffel symbols 