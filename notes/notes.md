# LED resistor calculation

## Collector resistor:


>>> (3.3 - 2) / 20e-3
64.99999999999999

where: 
- 2V is the forward voltage of the LED:
- 20e-3 A is the LED current

## Base resistor:

B -- beta
I_b -- Current base
V_be -- Voltage base-emitter

B = 160
I_b = 20e-3 / 160 = 0.00125 = 1.25 mA 

Voltage Base-Emitter is 0.7V:

R = (3.3 - 0.7) / 1.25e-3 = 2079.9

