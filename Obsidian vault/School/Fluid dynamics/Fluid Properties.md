**Fluid**: a substance that deforms continuously when acted upon by a [[shearing stress]] of any magnitude. Solid deforms then break, i.e. not continuously. 
![[Pasted image 20220717143629.png]]

Density: $\rho = \frac{mass}{volume}$
Specific weight: $\gamma =\frac{weight}{volume}$
Specific gravity: $SG_{liquid} = \frac{\gamma_{fluid}}{\gamma_{h20}}=\frac{\rho_{liquid}}{\rho_{h20}}$; for air, use density of air
Specific volume: $SV = \frac{volume}{mass}$
Ideal gas: $\frac{P}{\rho}=RT \text{, where P and T are absolute}$

> [!Fluid mechanics' problems requirements]
> 1. [[Conservation of mass]]
> 2. [[Newton's 2nd law]]
> 3. [[1st law of thermodynamics]]
> 4. [[2nd law of thermodynamics]]
### Viscosity: 
![[Pasted image 20220717180539.png]]
$\lim\limits_{d\theta\to0} tan(d\theta)=\frac{dx}{h}=d\theta$
Shear strain rate $\sim$ angular velocity
- angular velocity = $\frac{d\theta}{dt}=\frac{dx}{hdt}=\frac{Vdt}{hdt}=\frac{V}{h}=\frac{dV}{dh}$

Newtonian's fluid $\sim$ [[elastic deformation]]
- Linear relationship between stress and strain
- For solid
	- $\frac{shear stress}{shear strain}=$ [[Shear Modulus]]
- Similarly, for liquid
	- $\frac{\text{shear stress}}{\text{shear strain rate}}=viscosity=\frac{\tau}{\frac{dV}{dh}}$
> [!Definition for newtonian fluid]
> The ratio between shear stress and shear strain rate is ==*linear*==
> ![[Pasted image 20220717184159.png]]

$$\tau = \mu \frac{du}{dy}=\frac{F}{A}$$ 
- $\mu$ is the absolute/dynamic viscosity
	- $\frac{Ns}{m^2}=\frac{kg}{ms}$
	- ==Resistance to shear force==
- $\frac{du}{dy}$ is the velocity gradient.
- useful for determining shearing stress.

Kinematic viscosity: 
$$\nu = \frac{\mu}{\rho}=\frac{m^2}{s}$$
==think ratio of inertial forces to viscous forces==. It will manifest itself in [[Reynold's number]].

### No slip condition
- Fluid at the wall has the velocity of 0
- Not always true
- The tendency of molecules/atoms to stick to wall explains the phonomenon

### Pressure
Absolute Pressure: *pressure relative to zero*
Gauge Pressure: *pressure relative to a reference pressure*
$$P_g = P_{abs}-P_{atm}$$
Vacuum Pressure: indicates pressure drop from reference pressure - can be negative
$$P_vac = P_{atm}-P_{abs}$$

> [!Finding gauge pressure at different alt.]
> $$P_{gNew}={P_{abs}}-{\Delta P_{atm}}$$