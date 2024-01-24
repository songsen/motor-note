# motor-note
this is about BLDC motor control. 

# VESC: HOME PAGE
https://vesc-project.com/node/309

## observer
website: https://cas.mines-paristech.fr/~praly/Telechargement/Journaux/2010-IEEE_TPEL-Lee-Hong-Nam-Ortega-Praly-Astolfi.pdf

## git
https://github.com/vedderb/bldc/


Comparison Of Open Source Solutions
Open source solution	miniFOC	simpleFOC	ODrive	FpOC
Microcontroller	GD32F130G6U6	ATmega328P	STM32F405RGT6	FPGA
Driver chip	EG2133	L6234	DRV8301	MP6540
PID loop frequency	30kHz (max)	830Hz (max)	8kHz (typical)	18kHz (typical)
Whether have current loop	No	No	Yes	Yes
Driving power	90W	120W	960W	90W
Cost price (approx.)	20¥	100¥	300¥	150¥
    As can be seen from the table above, the scheme adopted by miniFOC can achieve high performance at low cost. At the same time, due to the re-selection according to the domestic supply chain, the selection of devices is not so limited, and there are many alternatives. amid the chip shortage in 2021, the cost of FOC still can be controlled at about 3$, which further proves the degree of cost optimization and the great potential of the project.
