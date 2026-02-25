# in Electrostatics
$$\Phi (\vec E , \vec, u, \vec v) $$

- on small scale - **const. flux** 
- $$\Phi = det(\vec E, \vec u, \vec v) = \epsilon_{ijk} E_i u_j v_k = \vec E \cdot \vec u \times \vec v =: \vec E \cdot \vec a$$
	with $\vec a$ as the [[normal vector]] to the $\vec u - \vec v$ - parallelogramm 
# though a surface 
$$\int_{\partial V} \vec E \cdot d \vec a$$
with surface being the **border** $\partial V$ of a Volume V 
		-> important: surface must be smooth enough = on a small enough scale it's a [[tangential surface]] 
		-> **surface elemtent** at a point: $$|\vec u| | \vec v| sin \theta_{uv} = |\vec u \times \vec v|$$
![[visual for flux through surface]]


# Calculating 
- [[Divergence theorem]] = Gauss theorem $$\int_V d^3 r (\vec \triangledown \cdot \vec F) (\vec r) = \int_{\partial V} \vec F \cdot d \vec a$$