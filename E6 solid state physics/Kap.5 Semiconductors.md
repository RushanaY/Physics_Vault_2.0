# 5.1 
## Classification of [[semiconductor]]s: 
- we use the [[energy band gap]] -> has to be less than $0 < E_g < 4eV$  
- at $T=0K$ all electrons are under the [[fermi energy]] have an infinite [[specific resistance]]  
- at $T> 0K$ resistance gets smaller because charge carrier get created thermaly 
- anuything bigger than zero -> less resistance -> current flows 


## types of semicoductors:
- [[intrinsic]] (pure) and [[dotiert]]e (mixed with other atoms) semiconductors 
- [[cristalline]] and [[amorph]] semiconductors 
- direct and indirect semiconductors (differ in their optical transitions)
- element semiconductors:
	- group IV: graphit, si ,gem zinn, P , se , te 
	- very pure stuff:[[Czochralski procedure]]  -> Silizium


how do we get those pure metalls????
- [[Czochralski procedure]] 
	- tale silizium  
	- melt it down
	- put in a small Si Impfkristall
	- Einkristall gets pulled out of the melted substance, while rotating
	- diamteter of this cylinder gets determined through rotation velocity and the pull veliocity 

Verbindungshalbleiter
- binary 
	- group III -IV
		- switch one electrons from an atom of the IV and II groups - >get a new material with properties liek an Elementhalbleiter 
		- iotnischer type of the bounding -> bigger band gap htan the normal material would have 
		- important: GaAs, AIAs, GaN, InP, InSb
	-  II -VI
		- more ionic than the II-CV semiconductor 
		- even bigger band gap
		- exeption is, if there is Hg in the connection 
		- important ones that work: CdD, CdSe, ZnTe, ZnO, HgTe
- ternäre 
	- legierung of two semiconductors 
- quantiär
	- also a Legierung 
	- with the properties 
		- [[Vergards rule]] $$a_{Al_xGa_{1-x}As}= x \cdot a_{AlAs} + (1 -x) \cdot a_{GaAs}$$
			which is a good approximation 
- important for the alloy components -> identical crystal structure, grid constant and radius of the ion also have to be similar 

## organic semiconductors 
- usually electrically isolating 
- if they have a conjugated binding system from double or triple connection or aromatischen Ringen , then they are electrically conductive 
- differentiation by molar mass
	- conjugated mass: Angharcen, Perylen
	- conucated Polymer: Polyanilin, POlkyacdtylen 
- they are cheaper to produce, are lighter and bendy
- porblem: don;t hold for very long and are not as stable 


# 5.2
## structure of the band 
- at $0K$ the [[fermi energy]] lies between two gaps 
- the botttom gap is called the **Valenzband** (VB) and the upper one is called the **Leitungsband** (LB) 
- the band gap is then the difference of the Maximum of VB -> VBM and the Maxmimum of the LB -> LBM $$E_g (T = 0K) = E_{LBM} - E_{VBM}$$
the gap is also temperature dependant: $$E_g (T) = E_g (T =0) - \frac{aT^2}{T _b}$$

## usage 
we differentiate between **direct** and **indirect** semiconductors: 
- direct
	- VBM and LBM are in the same point in the k space 
- indirect
	- VBM and LBM are in different points 

That's how it roughly looks like 
![[Kap.5 Semiconductors 2026-01-05 20.37.32.excalidraw]]




many important SC (semiconductor) have the properties of the [[angular momentum quantum number]] and the [[Spin quantum number]] :
- LB has $l=0$ 
- VB has $l=1$ 
- then the total angular momentum $j$ is for the bands:
	- LB: $j = 1/2$, $m_j = \pm 1/2$
	- VB: $j = 3/2$, $m_j = \pm 3/2$ (**heavy hole**) and $m_j = \pm 1/2$ (**light hole**) 
		- $j=1/2$ , $m_j = \pm 1/2$ (**spin orbit split hole**)
## spin orbit interaction 
because of the interaction the energy of **heavy and light hole gets increased** and the **energy of splitted hole gets decreased**
=> tha magnitude of the interaction is measured in $\Delta$ 
	$\Delta_{Ge} = 290meV$, $\Delta_{GaAs} = 350 meV$ , $\Delta_{Si} = 44meV$, $\Delta_{diamant}  =6 meV$ 

a light hole ->  a strong curvature gives a small [[effective mass]] $m_{lh}^*$ 
a heavy hole ->  small curvature gives a big effective mas $m_{hh}^*$ 


## important band structures 
- GaN 
- crystall structure 
- $Al_x Ga_{1-x}As$ 


## optical absorbece, relaxation, luminecence
SD become conducting when electrons from the VB get transported into the LB 
Ways of transporting:
- Exitation 
	- thermical 
		- at $T>0K$ the [[Fermi dirac distribution]] gets smeared and some electrons get thermically exited 
	- optically 
		- a photon of the energy that is bigger than $E_G$ gets absorbed by an electrin in the VB -> Absorbtion, this electron takes a free state in the LB ->  Interband Übergang 
	- to note: it is important to remember the conservation laws -> $\Delta k$ is very samll and the transition goes almost vertically in the [[dispersion relation]] 


## [[direct transition]] and [[indirect transition]]
- in an indirect transition very important is the **absorbtion/emission of a photon**  in order to fulfuill the conservation of momentum
- because we need an exptra parrticle, this transition is less likely to happen than just a direct one 
- in indirect SD absorbtion is possible only for $\hbar \omega > E_g$ (photons with the energy bigger than the energy gap)
describtion of the **absorbtion in asemiconductror**:
- [[absorption coefficient]] -> shows how much light looses intensity after going though a medium in x directoion 


for a SD with direct band we have $$\hbar \omega < E_g :D(\hbar \omega ) =0$$
$$\hbar \omega >= E_g : D (\hbar \omega) = \frac{1}{2 \pi} (\frac{2 \mu}{\hbar^2})^{3/2} (\hbar \omega - E_g)^{1/2}$$
and for the [[absorption coefficient]] will be expected $$\alpha \sim (\mu)^{3/2} \sqrt{\hbar \omega - E_g}$$

## fluoresence, relacaion, recombination 
-> is the opposite of absorbtion = electron goes from [[Leitungsband]] in an empty space inside the [[Valenzband]]
	=> this is called the [[recombination]] of $e^-$ and $h^+$ (those live only a couple nano seconds) and the process of them exchanging is also called the **relaxation** 
the energy that gets emitted in the process is called the [[fluoresence]] 


about the relaxation: 
- happens in the pair of recombined $e^-$ and $h^+$ 
- they love a couple nano seconds -> really short 
- **Relaxation**: the charge minimizes energy => they take the lowest states = highest states of the gap => emmit a photon 
- so usually an optical [[phonon]] gets emmitted till the energy of the charge is smaller than the one of the optical phonon
- rest of the relaxtion goes over acoustical phonons
- after it is done => recombination again possible 
- $E_{emitted} < E_{absorbed}$ 
- for indirect SD -> relaxation can happen at many different places 
	- then we alse have fluorosence because of the extra absorbtion/emission of phonons (this happens because we still have to follow the conservation of momentum) => this makes **recombination** less likely to happen and if it does, it is much slower 
	- Recombination can be 
		- radiativ - only photon emission 
		- non radiativ - no photons emitted -> here luminecense starts 


## luminecense, relatcaion and recombination 
now looking at the non radiative recombination 
two kindes:
- [[Fallunterstütze Rekombination]]
- [[Auger Rekombination]] 

## recombination compelte 
$$\frac{d n_{e,h}}{dt} = - k_{trap} n - k_{rad} n^2 - k_{auget}n^3$$ 

## [[ Quanteneffizienz]]  

## exit zones 
- optical exitation of an electron into the LB => creates an electron gap pair 
- the pair $e^-$ and $h^+$ can also interact between eachother => together they go into a special state = **exit zone** 
- the dielectric neightouhood $\epsilon (k)$ determines how much the interaction gets shielded 
- two types 
	- [[Wannier Mott exit zone]]
	- [[Frenkel exit zone]] 
- the particle inside the exit zone is the [[exiton]] 


## optical transition in two particle picture -> when there is an exiton 
![[Kap.5 Semiconductors 2026-01-13 16.54.27.excalidraw]]


## temperature dependance of the absorption spectrum 
- at room temeprature there are no effects 
- at low temperatures - a extit zone maxima appears and is more and more visible as the temperature drops 
- reason: the energy niveau gets wider with termal change because of the exiton-phonon coupling 
- 