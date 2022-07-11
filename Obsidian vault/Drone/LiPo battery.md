# Voltage and cell count
## LiPo anatomy
A number of LiPo ==cells== make up a LiPo battery. 
> [!Nomenclature and essence]
> One cell has a nominal voltage of 3.7V 
> cell = s $->$ 4S = 4 cells battery
![[Pasted image 20220711022052.png]] 
1S = 1 cell  = 3.7V  
2S = 2 cells = 7.4V  
3S = 3 cells = 11.1V  
4S = 4 cells = 14.8V  
5S = 5 cells = 18.5V  
6S = 6 cells = 22.2V

Lipo cell is designed to work between **3V and 4.2V**. If you discharge less than 3V, you can cause irreversible damage. If you charge higher than 4.2V, the battery could explode. 

## Capacity and size
Capacity is measured in mAh (milli-amp-hour)
> how much current the battery draws until it's empty in 1 hour.

> [!quick math trick]
> To see how long the battery will last given current amp draw, you take the rating and divide by the current amp draw. For example: you draw 30A continuously with a 1200mAh battery.
> $$time = \frac{1.2}{30}= .04 hr=2.4 min$$

There is a trade-off between capacity and weight, which affects flight time and agility of the vehicle. [Mathematical model for capacity vs flight time](https://oscarliang.com/how-to-choose-battery-for-quadcopter-multicopter/).

--- 
Reference: [Oscar's Liang: Everything about lipo battery for racing drone](https://oscarliang.com/lipo-battery-guide/)