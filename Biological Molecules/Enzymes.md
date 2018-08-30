---
title: "Enzymes"
output: html_document

--- 

# Imports

# Enzymes 

## Metabolic function 
Many biological reactions produce a lot of energy but occur too slowly to maintain a complex organism. Enzymes exert kinetic control overthermodynamic potentiallity, to speed up theses reactions to biologically feasible rates. Enzmyes in metabolism, accelerate and control biochemcial reaction rates. In particular they speed up the catabolism/dergradation of nutrients and generation/tranfromation of metabolites. Only very specialised regulatory enzymes, act to control biochemical reactions. Such enzymes are often found at juncture points in metabolic pathways, and act to  modify metabolic activity, (modifying the rate at which metabolic pathways act) to meet the cells biomchemical requirements.

## Distinctive features

### Catalytic power. 
Enzymes are distinct from other catalysts in part because they have a far higher catalytic power. (Catalytic power is calculated as a ratio of the rate of the catalysed reaction to the rate of the uncatalysed reaction)

### Specificty. 
Enzymes are highly selective, (they are not prominscuous) acting exclusively on specific substrate(s). One advantage of this selectivity is a decrease in the formation of biproducts. High levels of specificity are achieved by very specific shape and size of enzyme active site (complimentary to the substrate).

### Mild conditions 
happed under very mild conditions (pH and temp), as proteins suseptable to denaturation, furthermore often 

## Yield 
Yield decreases at each step in a multi step process, (yield is decreased at each step by the formation of byproduct)

## Regulation 
Not all enzymes are regulated only those which play key roles in metabolic processes. Regulation of these enzymes mantains appropriate levels of metabolic activvity to meet the cells biochemical requirements.  

## Taxonomy and Nomeclature
Enzymes are grouped into six different categories based on the reactions which they catalyse. 

![Relative number of differnt enzyme subgroups](Images/EnzymeGroups.jpg)

### Oxidoreductases. 
Catalyse redox reactions. 

### Transferases  
Catalyse reactions which involve the transfer of a moeity from one molecule to another. 

### Hydrolases.
Cleaves in organic substrates in the presence of water. Hydrolases are the most common type of enzymes. 

### Ligases. 
Catalyse reactions involving the formation of covalent bonds.  

### Isomerases. 
Catalyse reactions involving isomeric conversions. 

#### Lyases. 
Catalyse reactions involving the breaking of covalent bonds. 

### Enzyme commision number. 
Furthermore each enzyme is given an enzyme commision number which forms the standard classification system, however a 'common name' is also often used, especially in the case of metabolically important enzymes.  
 
## Graphical and Mathematic models

### Progession curves 
Progression curves show the change in conentration of a reactant/product agaisnt time. 

## Initial rate 
The initial rate $v_0$ in the reaction rate at t_0. 

NOTE: an increase in intital reactant concnetration leads to a higher inital rate. 

## Rate law 
The rate law for a reaction: \newline 

$a_1A_1+a_2A_2...\rightarrow b_1B_1+b_2B_2...$ \newline 

is given as: \newline 

$v=k[A_1]^{n_1}[A_2]^{n_2}$\newline 

where $n_1,n_2...$ are experimentally determined constants. 

NOTE: In the case of an elemental reaction, the exponents will be equivalent to the equilibrium coefficients. 

## Rate 
For the (elemental) reaction: \newline 

$a_1A_1+a_2A_2...\rightarrow b_1B_1+b_2B_2...$ \newline 

The instantanious rate of dissapearance of $A_1$ is given by:\newline 
$\frac{d[A]}{a_1dt}$ 

This rate can be related to the rate or dissapearance of other reactants and products as follows:\newline 

$v=-\frac{d[A_1]}{a_2dt}=-\frac{d[A_2]}{a_2dt}=\frac{d[B_1]}{b_1dt}=\frac{d[B_2]}{b_2dt}$ 




i## Enzyme Kinetics. 

### Maximum velocity 
Maximum catalystic rate\newline 
Donated by $V_{\text{max}}$

### Binding affinity
the strength of the bond/ enthalpy of bond formation \newline 
dontated by $K_m$

### Mechalis mention. 


#### Derrivation . 


##### Assumptions 
 #. The back reaction (E+P to ES in negligable.) $k_{-1}>>>k_2$ (Mechalis menten) 
 #. THe concnetration of the ES remains constant at a steady state (steady state assumption.) (Briggs- Huldane. )
 
 The inital velcoity can be expressed as a function of substrate concentration. 
 
 Total enzyme concentration: $[E]_T=[E]+[ES]$\newline ($[E_T]$) si known from the amount of enzymes added. 
 
$v=k_1[E][S]$ \newline 

$-v=k_{-1}[ES]$ \newline 

$k_2[ES]$ \newline 

By the constant rate approximation. 

$k_1[A][S]-k_{-1}[ES]-k_2[ES]=0$ \newline

(Look up coniditions or steay state assumption. )


$\rightarrow k_1[E][S]=k_{-1}[ES]+k_2[ES]$ \newline 
as $[E]_T=[E]+[ES]$ newilne
$\rightarrow k_1([E_T]-[ES])[S]=k_{-1}[ES]+k_2[ES]$
$\rightarrow \frac{([E_T]-[ES])[S]}{[ES]}=\frac{k_{-1}+k_2}{k_1}=k_M$ 

As $k_2>>>k_{-1}$\newline 

$(\frac{k_{-1}}{k_1})$ 

NOTE the unit of $K_m$ will be $mol\cdot dm^{-3}$


$\frac{([E_T]-[ES])[S]}{[ES]}=k_M$


$\frac{[E_T][S]}{[ES]}-\frac{[ES][S]}{[ES]}=K_M$ (solve for [ES])

$[ES]=\frac{[E_T[S]]}{K_M+[S]}$

Alsso as 

$v=k_2[ES]$ (rate o prouct formation). \newline 
$[ES]=\frac{v}{k_2}$ \newline 

$\rightarrow \frac{v}{k_2} = \frac{[E_T][S]}{K_M+[S]}$\newline

$\rightarrow v= \frac{k_2[E_T][S]}{K_M+[S]}$ ($[ES]\approx[E_T]$ for excess substrate) \newline 

$\rightarrow v=\frac{k_2[ES][S]}{K_M+[S]}$ $v=k_2[E_T]=v_{max}$ As ($[E_T]=[ES]$) for saturated solution. 

$v=\frac{v_{max}[S]}{{K_M+[S]}$ where v is the initial rate. 

$K_M$ and $v_{max}$ ca be used as general measures of catalytic ability. 

$K_M=[S]$ at \frac{v_max}{2}

$v=\frac{v_{max}[K_M]}{{K_M+[K_M]}=\frac{1}{2}v_{max}$ 

product concentration against time can be plotted and the tangent taken to give v at a given t. 


NOTE:

 #. either ony one susbstrte or concnetrtio o other substrates held constant. 
 #. E is in steady state. 
 #. reaction is irreversible., or 
 
 Copy down assumptions!!. 
 
 
 $\text{ln}(v)=\text{ln}(\frac{v_{max}[S]}{{K_M+[S]}})$
 
 $\rightarrow =$
 
NOTE: $v_{max}$ can be approximated}

## Thermodymanics. 
Thermodynamics is the study of the flow of energy.
Energy is obtained from food and utilised to perform biological functions.
bioenergetics of life. 

### Spontenaity. 
Thermodynamics can be used to determine which metaloic reactions will happen spontaneously. 

### Background 

#### System 
The portion of the universe which is of particular interest. 

##### Isolated 
The system can not exchange matter or energy with its surroundings. 

##### Closed 
Energy but not matter is exchanged with the surroundings. 

$$$$$ OPen 
Both energy and matter canb be exchanged with the surroundings. 

$$ Thermodynamics laws. 

### Fisrt Law.
The total energy of an isolated system is constant. 

### Second law. 
The total entropy of an isolated system cannot decrease but can only remain constant in the case of a system in eqillibrium or undergoing reversible reactions, or increasing when the system is undergoing reversible processes. 

## Internal energy 
The sum of all molecular kinetic (virbtarional rotational and translational) and potential mocecular energies. INternal energy is a state function so is independant of the path taken to reach it. 

$$$ Change
The internal energy of a system may change with the transfer of energy as heat or work. 

$\Delta E=w+q$ 

NOTE: The units for heat work and internal energy are joules. 

#### Aquisitive convention. 
w is positive when doen on the system. heat is positive when heat is transfered to the system. 

## Work 
PRessure volume work. $w=-p_\DeltaV$

$$$$Surroundings
The surroundings are everything other than the system. 

i## Enthalpy 
At constant volume $\Delta E=q_v$

$H=E+PV$ by definition. 

#### Change. 
$\DeltaH=\DeltaE+p\Delta V= q+w+P\Delta V= q-P\Delta V+P \Deta V =q$ (As pressure is constant in a biological environment)
$H=q_p$

Volume changes are minimal in biological systems (as reactions are not often in gasseous form) so $\Delta E \approx \Delta H$

$\Delta H$ is measured suing a calorimeter. 

$\Delta H ^\circ = -R \frac{d(lnK_{eq})}{d\frac{1}{T}}$

THe Van't Hoff plot gives delta H. 

On the y $Rln{K_{eq}}$ is plotted against $\frac{1}{T}$ on the x axis. so that the slope =$-\Delta H$
Endothermic is the absorption of heat. 

NOTE: the denaturation of an enzyme is endothermic because of H-bond breaking, and exposure of hydrophobic groups. 

## Enzyme kinetics. 

### $K_m$
For an enzyme catalysed reaction there is first order kinetics for low concentrations of substrate, tending towards zero order kinetics as substrate is increases to the point of enzyme saturation. 
$K_m=\frac{V_{max}}{2}$

A high $K_m$ indicates that a lot more substrate is necessary for the enzyme to become saturated, hence it indicates a low affinity for the substrate. 
A low $K_m$ indicates that the enzyme becomes saturated easily and has a high affinity for its substrate. 

#### favoured substrate. 
The enzyme with the lower $K_m$ will be favoured. 

### Turnover number/kinetic effeciency
Reffered to ass molecular activity ($K_{cat}$)  the turnover number indicates the maximal catalytic acitvity, defined as the number of substrate molecules converted into product per enzyme per unit time under saturating substrate concentrations. 

for the reaction $E+S \rightarrow ES \rightarrow E+P$  at initial conditios $K_{-2}$ is zero and $K_{cat}=k_2$ 

At saturationg substrate concentrations $v=v_{max} = K_2[ES]=$K_2[E_T]=\frac{v_{max}}{[E_T]}=k_{cat}$
NOTE: $k_{cat}$ is a first order rate constant (with units $s^{-1}$)

$k_{cat}$ is only informative at very high substrate concentrations which ins't physiological. (In the body normally $\frac{[S]}{K_M}<1$)
Vut we knwon $V_max=k_{cat}[E_T]$
So from mecahlis meten $v=\frac{v_{max}[S]}K_M{+[S]}$

As $[S]<<K_m$ 

$v=\frac{v_{max}}{K_M}$

At very low substrate concentrations $E_T$=[E]
So $v=\frac{k_{cat}}{K_m}$[E][S]


$\frac{K_{cat}}{K_m}$ is second measure of effeciency. It is the apparent second order rate constant for the reaction of enzyme and substrate to give poroduct.  
The higher this measure the better the kinetic effeciency and the berrer the affinity at low $[S]$ , i.e. the higher the catalyti effeciency of the enzyme. 

#### Catalytic perfection 
Enzymes which reach catalytic perfection are limited only by how fast the enproduct and enzyme can diffuse together. Rate of diffusion of enzyme and substrate in solution.  (maximum value is about $10^{8-9}$)

NOTE: $\frac{K_{cat}{}K_m$ applies to the initial region of the [S] vs rate graph, whereas $K_{kat} reprisents the later region onces $[S]^0$ . $v_0$=k_{cat}[E]^1[S]^0
$V_0=\frac{k_{cat}{K_m}}[S][E]$

## Enzyme inhibition 

### reversible 


### reversible
binds non eqilibrium 

#### Compeditive 
Inhibitor binds only to the free enzyme (so has to bind (often )) to the actvie site and so must look like the enzyme. 
Compeditative inhibitors increase $K_m$ by lowering the effective substrate concentration. 
$V_{max remains constant}$


#### uncompeditative 
THe inhibitor will only bind to the enzyme substrate complex. $V_max$ drops as EI complex formed which lowers [E] $K_m$ also decreases (because of the law of mass action, leads to an increase in affinity. 

Line weaver burk is a series of parallel lines. $\frac{V_max}{}K_m$) the slope, does not change. 

#### non compediitve. 
Can bind to enzyme enzyme substrate or both 

##### Pure 
When the affinity for the enzyme or the enzyme substrate complex is identical it is ppure

##### Mixed 
IF the affinity for the enzyme and the enzyme substrate complex differs then the enzyme is mixed. 

## Bisubstrate reaction 
Two substrates interact with the enzyme 

### Single displacement/ sequential 

### Random 
There are two substrate binding sites, so substrates can bind in any order. 

### Ordered
Binding of one substrate inductes the formation of a second substrate binding site by a conformational change within the enzyme its.


### Double displacement.
Follow the pingpong method. The first substrate binds and covalently modifies the enzyme (leaves part of itself behind) . The second substrate can then bind, takes the part left by the first substrate onto itself and is then released. 

## Thermodynamics second law. 
The entropy of an isolated system can only decrease or remain constant (in eqillibrium or when reversible processess aer taking place. )Entropy reprisents energy dispersion. 

$S=kln(W)$
where w is the number of microstates

Moving from disorder to order requires energy input in the form of work. (this is of particular importance in a biological system where reactions, at least catabolic reactions involve the formation of highly ordered macromolecules. 

### Third law 
$S=\displaystyle\int ^T _0 C_pdlnT)$ the absolute entropy of a perfect cystal at zero degrees kalvin is zero. . 


### Heat capacity 
$C_p=\frac{dH}{dT}$

the heat capacity is the amount of heat required to increase 1 mol of substance by one degree. 

#### $\Delta C_p$ 
Positive change implies more heat stability. which implies that the molecules have new ways to move so more enrgy can be added for a temperature increase. Conversely if the change in $C_p$ is negative there are less ways of motion. 

### Free energy 
The free energy gives the spontenaity of the reaction

$\Delta G=\\Delta H -T\Delta S$ when change in gibbs free energy is zero the enthalpic and entropic compoents are equal. at this point the reaction is at eqilibrium. A spontaneous/ exogonic reaction has a negative $\Delta G$ 

NOTE:remeber the $\Delta G$ indicates the enrgy change between the reactants and products. 

If $\Delta H$ is positive the reaction is said to be enthalpically opposed, or in the case of  negative $\Delta S$  the reaction is entropically opposed. (the opposite of opposed is favoured. 

Free energy entropy are temperature dependant, so the temperature range of the experiment must be specified. backspace32

#### for non standard conditionbackspace32

$\Delta G= \Delta G ^\circ RTln(\frac[C][D]){[A][B]}$

$\Delta G =-RTln (K_{eq})$

In biological conditions we use a modified standard state $\Delta G^\circ '$ which means pH is at seven .


NOTE: a comparison of several thermodynamic parameters can give a reasonable idea of the reaction, one on its own is not particularly useful. 

ie for protien unfolding, $\Delta G$ is positive, $\Delta S$ will be positive. 


## Analysis of processes according to thermodynamics. 
Determine entropically and enthalpically opposed /favoured. If a reaction still occurs it can be called enthalpically/entropically driven. 
Th dissolution of a polar substance in water leads to a decrease in heat capacity whereas the dissolution of a non polar substance increases the heat capacity, this is becuase during solvation the water molecules form a solvation/hydration shell around polar substances reducing the freedom of their moviment. 
In the case of hydrophobic molecules water formes an ordered cage, clathrate cage, around the hydrophobic molecules, interacting with eachother as a pose to the hydrophobic molecule. The clathrate is more laible (that is more free to exchange hydrogen bonds. Liable waters result in a positive change in heat capacity because they have more ways to store energy. )

Protein folding. There are more hydrophobic groups exposed as a protein unfolds, leading to increase in the $C_p$, conversely when a portein folds these groups are removed from solution and therefore the heat capacity decreases. (also freedom of movement of the protein) 

NOTE: the hydration shell is not just the water dirrectly in contact with the ion but also in layers outwards as if the shell orientates one way then the outside ones also orientate with respect to those. 

NOTE: remember all of the thermodyamic parameters are constant. 


NOTE: Pracs start at 2, test covers everything done in enzymes connetcs, but focussed on the lab and there is lab prep work. 

NOTE: water will formed orded shells areound charged ions making them more ordered. 



NOTE: remember $\Delta G$ gives an indication of the equilirium position. 

NOTE: ATP does not have the highest energy of hydrolysis or the lowest, with regard to the energy shuttle mollecules, ie it is intermediate. This is important as it can take nergy from very high energy phosphates and release energy to from lower energy phosphate compounds. Because energy can be tranferred by ATP in this way it is known as the energy currency of the cell. 


### Chemoheterotrophes. 
Consume organic molecules and release the stored energy in a series of oxidative reactions. 


###__EnergyCurrencyMolecules: Energy Currency Molecules__ 

###__ATP: Adenoside Triphosphate__

lab test on friday from thermodyamics to end of wednesday lectures, from 
enthalpy entropy prac. 


### Kinase enzymes. 
transfer a phosphate group. 

### phosphatase
a dephosphorylating enzyme. 
