1st meeting: 
- Our main objective: 

> We want to control the flow of fluids with hardware as well as gather and process data from sensors. All of which should be done in a simple robust manner; by that i mean everything should be visible and controllable through GUI. 
- Timeline: 
	- summer to first 1/2 of fall: 
		- complete simple arduino project. We would also be able to use this for onboarding purposes. 
		- learn about calibration and principles of different sensors/components
		- rough budget for real parts
		- Be flexible
	- Fall -> winter
		- Sensors mounting schemes
		- Operating protocols/sequences
		- Parts procurement
		- finish building control system (wiring/soldering, pcb, code, and test)
		- water test!
- Arduino onboarding/learning project:
	- we'll work on something that incorporate sensors, camera, and motors (i'll have to check for what sensors i have around when i get back to Davis)
	- transferring data to host pc
	- design a gui (matlab, python, javascript, or c#)
- DAQ options
	- as of now im leaning towards stm32 platform (nucleo boards)
--- 
Other notes from Emmet and Thomas:
- refers to the txt file thomas dropped here
- timing things is a bit**
	- use interrupts()
	- synchronising signals is hard. IE: getting different data all at once
- colleting data all at once is not possible with single thread CPU
	- look into multi-threading
	- LPG uses 1 MCU for actuating, 1 MCU for data acquisition, Pi to process data, PC to organize and display data
- Use RJ45 rather than USB
- MOSFET > BJT
- Have separate grounds for analog and digital signals; this will gives 'true-er' signals.
- Custom PCBs would be helpful with organizing and being modular
- No fancy signal processing if you don't need it (DSP)
- Building things modular
	- this will help compare quality of data when we switch/replace different parts
	- replacing parts will be easier
	- upgrading will be easier
	- dupont and standoffs
- MATLAB is shit 
	- lots of overhead loading ~ slow
	- not very optimized
	- use python, c, or something else
- CS seems to be more intensive than expected (besides interacting with hardware)
	- database
	- web socket
	- docker container
	- multithreading
	- communications