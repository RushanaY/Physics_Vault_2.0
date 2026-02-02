## Structure of matter:
- **solid body**  $\ge 100 nm$ in typicala energy scale of $\sim 0.1 ... 1eV$
- **atom** $\sim 0,1 nm$ in typical energy scale of $\sim 10eV ... 1keV$ 
- **[[nucleus]]** of the atom  $\sim 10 fm$ (four times smaller than atom) in the energy scale of $\sim MeV$
- **[[proton]]s and [[neutron]]s** both $\sim fm = 10^{-15}$ and energyscale $\sim 6eV$ 
- **[[quark]]s**  $<0.01 am = 10^{-20}$ being in the energy scale of $\sim TeV$. The same parameters apply for an electron, which is therefore also an elementarteilchen 
Anything, whatever, might be smaller than a quark $\ll am$ will have energies $>> TeV$ 

**[[Resolution]]** is directly dependant on wave length and that is dependand on energy: Auflosung $\leftrightarrow$ wavelength $\leftrightarrow$ energy.
This is also shown in the criteria/euqation $$E = \hbar \omega = \hbar \frac{c}{\lambda}$$ where $\lambda = \frac{\lambda}{2 \pi} = \frac{\hbar c}{E}$, which applies fro massless objects. For both mass and masseless objects it would be the [[de Brogli wavelength]] $\lambda = \frac{\hbar}{p}$ 
Energy is th universal unit 

Conversion:
Given the constants: 
- $\hbar = \frac{h}{2\pi} = 1.0545717 \cdot 10^{-19}Js$
- $c = 299792458 \frac{m}{s}$ 
- $1 eV = 1.60219 \cdot 10^{-19}....$
- $(\hbar c)^2 = 0.3896 eV^2 \cdot 0.1 fm^2$ (this is a fento square meter) in the [[barn]] : $1b = 10^{-24} cm^2 = 10^{-28}m^2$
$\Rightarrow$ $$\hbar = 0.658 eV \cdot fs$$$$\hbar c = 197 MeV \cdot fm $$$$(\hbar c)^2 = 0.3896 b $$

lengh/time/charge/energy

lenght is dependand on random units, so in order to define a length the so called  [[natural unit]]s are used: $$\hbar = 1, c =1, \epsilon_0 =1$$those make the calculations easier and are kind of implied for the lectures (?)
Therefore: $$\text{length} \sim \frac{1}{\text{energy}}, \text{time}=\frac{1}{\text{energy}}, \text{charge} \sim 1$$
=> $\alpha_{em} = \frac{e^2}{4 \pi \epsilon_0 \hbar c}=\frac{1}{137}$ defined the [[Fine structure constant]]  (is dimentionless)

there are no naturliche units for energy => $eV$ is energy (in Kern und Teilchenphysik)

# 1.1. Grundbegriffe von Streuexperimenten 
[[Scattering]] experiments are the central tool to look at nuclei and particles. A particle A gets scatters onto particle/nuclei B and observe the products C,D,.... 
it can be represented with the ![[Feynmann diagramm]]
Kinematic :
- energy-, momentum-, angluar momentum conservation hold 
- kinetic energy: $T_A+T_B = T_C +T_D + ...+ Q$(innere Energy)
- relativistische energie: $E_A + E_B = E_C + E_D+ ...$ (here the innere energy is already inside)
- same thing but with inertia $\vec p_a + \vec p_B = \vec p_C + \vec p_D + ...$ 

Connecting energy and inetria we use a Viererimpuls p $$p = \begin{pmatrix} E/c \\ \vec p \end{pmatrix} = \begin{pmatrix} E/c \\ p_x \\ p_y \\ p_z \end{pmatrix}$$
$\Rightarrow$ $p_A + p_B = p_C + p_D+ ...$ 

[[Lorenz transformation]] of the Viererimpuls for $\vec v = \begin{pmatrix} 0 \\ 0 \\ v \end{pmatrix}$ 
$$\vec p' = \begin{pmatrix} E'/c \\ p_x' \\ p_y' \\ p_z'  \end{pmatrix} = \begin{pmatrix} \gamma & 0 & 0 & \beta \gamma \\ 0 & 1 & 0 & 0 \\ 0 & 0 & 1 & 0 \\ \beta \gamma & 0 & 0 & \gamma \end{pmatrix} = \begin{pmatrix} E/c \\ p_x \\ p_y \\ p_z\end{pmatrix}$$

for a particle at rest: $E = mc^2$, $p_x = p_y = p_z = | \vec p|=0$ $\Rightarrow$ $E'= \gamma mc^2$, $p'_x = p'_y = 0$,    $p'_z = - \beta \gamma mc= -|\vec p'|$ 
in general we use the equations: $$\gamma = \frac{E}{mc^2}, \space \vec \beta \gamma = \frac{\vec p}{mc},\space  \vec \beta = \frac{\vec pc}{E}$$
- Lorenzinvariance of a [[Four momentum]]
- if we have scattering: $A+B \to C+D+...$ (two elemtns colliding and falling apart)
	- we define the centre of mass as $$S^2 := (p_A + p_B)^2/c^2$$
- differentiating bw two cases
		- **fixed target**
			- particle A is moving and particle B is fixed
			- $A = (E/c^2 + m_B)^2 - E^2/c^4 = 2Em_B/c^2$ 
		- **collider**
			- both particles are moving towards eachother 
			- $S = (2E/c^2)^2 - 0 = 4E^2/c^4$ 
		- [[Mandelstem Variable]]n $$s = \frac{(p_A + p_B)^2}{c^2}$$$$t = \frac{(p_A - p_C)^2}{c^2}$$$$u = \frac{(p_A - p_D)^2}{c^2}$$

# 1.2 differnetieller Wirkungsquerschnitt 
differential cross section is the area that gets hit and is dependant on the type of interaction, energy and more
![[differnetial cross section]]
**Ray**:
- number of particles per time unit: $\dot{N}_S$ 
- ray cross section area :$F$ 
- [[flow rate]]: $$\phi_S = \frac{\dot{N}_S}{F}$$
**Target**:
- number of target particles inside the ray :$N_T$ 
**Detector**:
- number of scatterd particles per time unit: $\dot{N}$

From this we can derive useful formulas"
- [[cross section]]/Wirkungsquerschnitt $$\sigma = \frac{\dot{N}}{\phi_S \cdot N_T}$$
- [[luminocity]] $$\mathscr{L} = \phi_S \cdot N_T \Rightarrow \dot{N}= \mathscr{L} \cdot \sigma \Rightarrow \Delta N = \sigma \int \mathscr{L}dt $$
	- [[luminocity of collider]]$$\mathscr{L} = \frac{N_1N_2}{4 \pi \sigma_x \sigma_y}\cdot f \cdot B$$
		- $N_1,N_2$ number of particles per point
		- $4 \pi \sigma_x \sigma_y$: collision area
		- $f$: circulation frequency/ Umlauffrequenz
		- $B$ : number of Strahlpakete/beam pacadge?
**Differential cross section** - per [[solid angle]]  $$\frac{d \sigma}{d \Omega}= \frac{1}{\mathscr{L}}\frac{d \dot{N}}{d \Omega}$$

## [[Rutherford scattering]]
has the differential cross section in the classical case:$$\frac{d \sigma}{d \Omega} = \frac{b}{\sin \theta} \frac{d b}{d \theta}$$
where b is the [[impact parameter]] 
$$(\frac{d \sigma}{d \Omega})_{Rutherford} = (\frac{z \cdot Z \cdot e}{4 \pi \epsilon_0 \cdot E_{kin}})^2 \cdot \frac{1}{\sin^4(\theta/2)} = \frac{z^2 Z^2 \alpha^2 (\hbar c )^2}{16 E^2_{kin}}\frac{1}{\sin^4 \theta/2}$$
![[Rutherford diagramm]]where having an angle of $180$ degrees leads to backwards scattering

[[thoughts on E5 books]] 