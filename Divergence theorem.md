Gradientensatz, Gauss theorem 
$$\int_V d^3 r (\vec \triangledown \cdot \vec F) (\vec r) = \int_{\partial V} \vec F \cdot d \vec a$$
Use the coordinates that suite you best: [[surface integral in any coordinates]] 
$$= \int dq_1 \int dq_2 f(q_1, q_2 ), \space \space f(q_1, q_2) = F_i (\vec r (q_1, q_2)) \frac{\partial r_j}{\partial q_1}\frac{\partial r_j}{\partial q_2} \epsilon_{ijk}$$

# in Electrodynamics
$$\int_{\partial V} \vec E \cdot d \vec a = \int_{v} \frac{1}{\epsilon_0} \rho d^3 r$$
in words (ED): **Flux of $\vec E$ throgh an area = enclosed charge** 
-> is basically the source of any charge 

**about the naming**:
- "Gauss'scher Satz" = mathematical
- "Gauss'sches Gesetz" = used in Electrodynamics


**Procedure**:
1. find [[chart]] of the Volume
2. do integral

Therefore we know: 
- $\vec \triangledown \cdot \vec E = \frac{1}{\epsilon_0} \rho$  holds 
- $\vec \triangledown \cdot \vec E = 0$ => dencity of field lines is proportional to E

**Cases**: 
- field inside a **hollow sphere**: 
	for: Radius R, charge Q, using symmetry -> $\vec E || \vec a$ 
$$\int_{|\vec r| = R} \vec E \cdot d \vec a= 4 \pi R^2 | \vec E | = \int_{|\vec r| < R} d^3 r' \vec \triangledown \cdot \vec E = \epsilon_0^{-1} \int_{|\vec r|< R} d^3 r' \rho(\vec r')$$
	- $= \epsilon_0^{-1} Q$ for R outside
	- $=0$ for R inside
- field inside an infinetly long, homogeniuous charged **cylinder**: 
- fiel inside a homogeounus, charged **sphere**: 

