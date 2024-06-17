# Stealthburner_Toolhead_PCB
Wiring Stealthburner Toolhead PCB from Hartk1213
This this how I wire my PCB Hartke to my MCU using an fystec wiring loom:

PCB 
label	MCU	Wire AWG	SKR E3 v3
label	Pin SKR 	Cable Label
24V	HE0 +V	20	PSU +V	V+	+24V
GND	PSU -V (NOT MAINS GND)	24	PSU -V	V-	GND
PROBE(Z)	Probe Signal Pin	24	Z-Stop	PC2	PROBE
HE0	HE0 -V	20	E0	PC8	HE0
5V	5V	24	PSU +5V	V+	+5V
PCF	Part Cooling Fan -V	24	FAN 0	PC6	PCF
HEF	Hotend Cooling Fan -V	24	FAN 2	PB15	HEF
AGND	Hotend Thermistor -V	24	TH0	GND	AGND
TH0	Hotend Thermistor Signal Pin (TH0)	24	TH0	PA0	TH0
AUX	Auxillary (X-Stop)	24	X-Stop	PC0	AUX
S1A	Red Stepper Wire	24	EM	1A	S1A
S2A	Green Stepper Wire	24	EM	2A	S2A
S1B	Blue Stepper Wire	24	EM	1B	S1B
S2B	Black Stepper Wire	24	EM	2B	S2B
LED	Neopixel Data Pin	24	Neopixel1	PA8	LED
FS	ERCF Filament sensor	24	/	/	/


Sources here : https://github.com/hartk1213/MISC/tree/main/PCBs/Stealthburner_Toolhead_PCB
