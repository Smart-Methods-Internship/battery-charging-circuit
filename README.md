# battery-charging-circuit
This circuit is designed to charge Li-ion batteries. Li-ion batteries are best for robots due to their portability and energy density. 
Energy density is basically the amount of energy stored in a given system per unit volume.. An average 1.5V Li-ion battery has an energy density of 100-265 Wh/kg or 250-670 Wh/L.
The C rating of the 1.5V Li-ion batteries are around 300mA/h. This make them ideal for robots and equipment that require quick charging.
Moreover, the lifetime of Li-ion batteries is 2-3 years. 
The only drawback would be the slightly higher price, but the advantages of using Lithium batteries outweighs the disadvantages.
In this circuit, we use a variable voltage regulator IC LM 7805. A DC power supply is used to supply power to the entire circuit. 
Charging current passes through D1 to the voltage regulator IC LM 317. By adjusting its Adjust pin, output voltage and current can be regulated.
The voltage regulator is placed between the adjust pin and ground to provide an output voltage of 9 volts to the battery. 
Resistor R3 restrict the charging current and diode D2 prevents discharge of current from the battery.
Transistor T1 and Zener diode ZD act as a cut off switch when the battery is full.
