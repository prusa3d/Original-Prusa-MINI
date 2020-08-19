### Recommended print settings :

Printer : **Original Prusa i3 MK3S**

Print settings : **0.20mm Quality**

Material : **Prusament PETG**

Nozzle : **0.4 mm**

Layer : **0.2 mm**

Support : **no supports**

### **Edit :**

Infill pattern : **grid**

Infill density : **10 %**

<br/>

### **Parts :**


- MINI-z-bottom-cover

- MINI-z-bottom-cable-cover

- MINI-fan-spacer

- MINI-fan-spacer-clip

- MINI-fsenzor-box

- MINI-fsenzor-cover

- MINI-fsenzor-lever

- MINI-minda-holder

- MINI-inspection-door

- MINI-knob

- MINI-heatbed-cable-cover-bottom

- MINI-heatbed-cable-cover-top

- MINI-rail-spoolholder

- MINI-base-spoolholder






-------------------------------------------------------------------------------------------------------------------

### Recommended print settings :

Printer : **Original Prusa i3 MK3S**

Print settings : **0.20mm Quality**

Material : **Prusament PETG**

Nozzle : **0.4 mm**

Layer : **0.2 mm**

Support : **no supports**

### **Edit :**

Infill pattern : **grid**

Infill density : **20 %**

<br/>

### **Parts :**


- MINI-x-carriage

- MINI-x-end

- MINI-y-belt-holder

- MINI-y-idler

- MINI-y-plate-rear

- MINI-y-plate-front

- MINI-z-carriage-rear

- MINI-z-carriage-front

- MINI-z-bottom

- MINI-z-top

- MINI-extruder-rear

- MINI-extruder-front

- MINI-extruder-idler

- MINI-display-box






-----------------------------------------------------------------------------------------------

Please keep in mind thermal expansion of used material especially in XY plane. Printed parts are tempered by heatbed - then cooled down to room temperature so parts shrink.

```
Apply this linear relation: delta D´ = D * gamma * delta T
	delta D´	= final dimension difference
	D		= original dimension
	gamma		= coefficient of thermal expansion for used material
	delta T		= printed part temperature difference between current temperature 
			  while it's printed and ambient temperature in use

Example:
material	PETG: 	HB temp. = 90 [°C]
			amb. temp. = 25 [°C] 
delta T		90 - 25 = 65 [°C]
gamma		0.000068 [m/m*°C] [1/°C] (doesn't matter if Celsius or Kelvin)
D		100 [mm]
Use basic unit!

delta D´ = D * gamma * delta T
delta D´ = 0.1 * 0.000068 * 65
delta D´ = 0.000442 [m] = 0.442 [mm]
```

Linear thermal expansion works for each layer if there's any delta T but every layer has different delta T if the heatbed temperates printed part - the higher layer position the smaller delta T. It's due to cooling printed part by ambient air and air flow from print fan.
