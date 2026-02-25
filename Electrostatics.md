same [[Maxwell equations]], but with $$\vec B (\vec r, t) = 0, \space \space \partial_t \vec E (\vec r, t) = 0$$
in this case: 
# field of a point charge 
at the place $\vec r_0: \rho(\vec r) = q \delta (\vec r - \vec r_0)$, where $\delta$ is the [[delta function]]
$$\vec E (\vec r) = \frac{q}{4 \pi \epsilon_0} \frac{\vec r - \vec r_0}{|\vec r - \vec r_0|^3}$$

using [[Greens function]]: $$-4\pi \delta (\vec r) = \triangle \frac{1}{r} = \vec \triangledown \cdot \vec \triangledown \frac{1}{r} = - \vec \triangledown \cdot \frac{\vec r}{r^3}$$
intersting case - the singularity. We can look at it, but definining the derivative at the [[singularity]] :
$$\int_{\mathbb{R}^3} d^3 r f(\vec r) \triangle \frac{1}{r} := - \int_{\mathbb{R}^3} d^3 r [\vec \triangledown f(\vec r)] \cdot [\vec \triangledown \frac{1}{r}] : = \int_{\mathbb{R}^3} d^3 r [\triangle f)\vec r)) ] \frac{1}{r}$$

# Couloumb force
= force between **two** point charges $q_1, q_2$ at places $\vec r_1, \vec r_2$ with the vector connecting them: $\vec r_{12} : = \vec r_1 - \vec r_2$
$$\vec F = \frac{q_1 q-2}{4\pi \epsilon_0}\frac{\hat r_{12}}{|\vec r_{12} |^2}$$with notation for [[unit vector]]: $$\hat r := \frac{\vec r}{r}$$
in case: **multiple** point charges -> continuous charge distribution 
- we use the linearity of forces (*same idea that allows us ti just add the forces up, without worrying about how they might react with eachother*)$$\vec E(\vec r) = \frac{1}{4 \pi \epsilon_0} \sum_i q_i \frac{\vec r - \vec r_i}{|\vec r - \vec r_i|^3 } \Rightarrow \vec E (\vec r)  = \int d^3 r' \rho(\vec r') \frac{\vec r - \vec r_i}{|\vec r - \vec r_i|^3 }$$
- continous distribution is the case, when we have so may charges, that the seperate point charges melt into $\rho (\vec r) d^3 dr$ 

[[Field lines]]  
-> I guess it helps the visualisation of the divergenze around a charge
more : "Zu Gauss.pdf" from moodle
