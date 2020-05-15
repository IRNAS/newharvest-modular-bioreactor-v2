## Incubator
The incubator is a housing for cell and tissue culture, which requires manual adjustment and automatic regulation of atmospheric conditions (temperature, CO2) without overshoot, ease of disinfection, aseptic use and alarm notifications. In addition, this prototype will provide wireless connectivity and control and have a transparent door for sample observation without opening. The prototype will be built from a modified thermoelectric wine-cooler.

| Parameter				| Value									|
| --- | --- |
| Build:				| Thermoelectric wine cooler Klarstein 10029816 (Chal-Tec GmbH) - modified|
| Physical dimensions:	| Inner: 17 x 31 x 52cm (35l)			|
| 						| Outer: 26 x 50 x 55cm					|
| Weight: 				| Approx. 15kg							|
| Power: 				| 70W									|
| Number of trays:		| 4										|
| T regulation range: 	| Room temperature - 40°C ± 0.5°C		|
| T sensor:			 	| SHT31(Sensirion AG)					|
| Heat source: 			| Built in peltier element				|
| Heat distribution: 	| Built in fan + tray fans				|
| CO<sub>2</sub> regulation range:	| 0 - 10% (100,000ppm) ± 0.1%		|
| CO<sub>2</sub> sensor:	| ExplorIR-M-20	(CO2meter)		|
| CO<sub>2</sub> source: 			| external							|
| CO<sub>2</sub> distribution: 	| Built in fan + tray fans				|
| Regulation: 			| Automatic adjustment to set values	|
| Monitoring/control:	| ESP32 microcontroller					|
| 						| Digital display + control buttons		|
|						| Wi-fi + web interface 				|
| Tray size:			| 18x29cm								|


## Tray
### Pumping system
The pumping system on each tray will be composed of two oscillating syringe pumps, which will exchange nutrient medium between two syringes through the culture dish. The pumping system will allow automatic regulation and manual adjustment of medium flow, as well as motor position using control buttons and a wi-fi connected web interface.

| Parameter				| Value									|
| --- | --- |
| Build:				| Aluminium								|
| Charging:				| Powered by incubator housing, battery, external power supply |
| Pump:					| Syringe pump, stepper motor driven lead screw mechanism |
| Syringes:				| 2x20ml (Braun Omnifix with luer-lock) |
| Flow:					| 0.05 - 2ml/min ± 0.01ml/min |
| Tubing:				| Cell culture silicone (biocompatible, autoclavable) |
| Tubing connections:	| Luer-lock (polypropylene) |
| Dead volume:			| <5ml |
| Monitoring/control:	| Digital display, control buttons, Wi-fi with web interface |
| Control parameters:	| Flow-rate, motor position |
| Sensors:				| Motor limit switch, temperature |

### Bubble trap ( = debubbler)
Two bubble traps/debubblers will be installed per tray in between the culture dish and each syringe pump to prevent possible air bubbles from entering the tissue samples during medium flow from either side. As a consequence, each membrane based unit will also allow gas exchange by diffusion.

| Parameter				| Value									|
| --- | --- |
| Build:				| Custom construction (PEEK)			|
| Membrane:				| PTFE, 0.2µm porosity					|
| Maximum flow-rate:	| 2ml/min (both directions)				|
| Tubing connection:	| Luer-lock								|
| Other features:		| Autoclavable, leak-proof				|


### Perfusion unit for 6-well plates
This module allows connecting circulation to a standard 6-well plate, that can be used for standard cell biology experiments. Individual wells are coupled into a perfusion stream, which is controlled externally. The perfusion unit, built as the well plate cover has an oppening above every well, allowing visual sample evaluation during the experiments. To sustain aseptic work an additional cover is recommended, such as gas permeable cover membranes.

| Parameter				| Value									|
| --- | --- |
| Build:				| Custom construction (PEEK) |
| Sample container:		|6-well plate. |
| 						| Sample insert/exchange in 1 step without additional tools. |
|Perfusion:				| Silicone tubing connected via luer-lock. |
| Other features:		| Autoclavable.|
| Requirements:			| Gas permeable well-plate cover membrane. |


### Custom 3D muscle tissue platform
The custom-made culture dish will be adapted for the perfusable New Harvest tissue samples and will fulfill the following functions: Allow simple inserting and exchange of samples, as well as attaching them to the perfusion system via catheter, while being leak-proof. The samples will be kept in place, however, the container will allow contractions of the sample. The housing will be autoclavable, suitable for reuse and allow assembly without additional tools. In addition, the cover will contain a glass window made from standard microscope slides to allow observation without disturbing the samples.

| Parameter				| Value									|
| --- | --- |
| Build:				| Custom construction (PEEK) |
| Sample container:		|Holding sample in place while allowing contraction and extension in Y and Z directions. |
| 						| Sample insert/exchange in 2 steps without additional tools. |
|Perfusion:				| Leak-proof catheter (peripheral venous type) insert/fastening in 2 steps without additional tools, luer-lock connectivity. |
| Other features:		| Autoclavable, transparent glass window (microscope slide) |
| Requirements:			| Precise, repeatable sample size |

