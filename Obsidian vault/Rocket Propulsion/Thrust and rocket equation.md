# Thrust and rocket equation
## Thrust 
- Reaction force acting at COM
	- Experienced by vehicle's structure from propellant ejection
- Ejection gas [[momentum]] -> Newton 3rd Law [[Newton law of motion]]
	- $$F = \frac{d(mv_e)}{dt} = \dot mv_e$$ 
		- $V_e$ is exit velocity of the gas
	- However, only work if gas pressure and atmosphere pressure are == -> more generalized formula:
	- $$F=\dot mv_{e}+(p_{e}-p_{a})A_{e}$$
		- $p_{e}$ is exit pressure of gas
		- $A_{e}$ is nozzle area
		- $p_a$ is ambient pressure	
		- It really is just Newton 3rd law holistically
		![[Pasted image 20220708175622.png]]
		> why is under expanded not ideal?
		 > If it loses efficiency, then does it also lose thrust?
### Exhaust Velocity 
> $$c=\frac{F}{\dot m}=I_sg_0=v_2+(p_e-p_a)\frac{A_e}{\dot m}$$
> The Russians use c to measure efficiency in lieu of $I_s$, which is a [[Rocket Efficiency]] measurement. $c \propto I_s$
- $V_2$ is the gas exit velocity
> ==gas exit velocity =/= effective exhaust velocity==
> gas exit velocity is part of effective exhaust velocity
   #### C* - cee star
   - cee star is characteristic velocity =/= physical velocity similar to [[Head loss]]
   - independent of nozzle geometric characteristics
   - related to efficiency of the combustion process
   > $$c* = \frac{p_0A_t}{\dot m}$$
   > $p_0$ is stagnation pressure ^[[[Chamber Nozzle Theory]]], but we can assume chamber pressure
   > $A_t$ is throat area

