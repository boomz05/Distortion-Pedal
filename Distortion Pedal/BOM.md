# Bill of Materials

This BOM follows the schematic. During breadboard debugging, the two 1N4148 clipping diodes were replaced with LEDs because the available diodes were faulty.

| Reference | Component | Value / part | Quantity | Notes |
| --- | --- | --- | ---: | --- |
| Q1, Q2 | NPN transistor | 2N2222 | 2 | Buffer and gain stages |
| D1, D2 | Signal diode | 1N4148 | 2 | Schematic value; LEDs used in the prototype |
| R1, R15 | Resistor | 100 Ω | 2 | Input and supply filtering |
| R6 | Resistor | 1 MΩ | 1 | Q1 bias |
| R7 | Resistor | 1.2 MΩ | 1 | Q1 bias |
| R8 | Resistor | 10 kΩ | 1 | Q1 emitter resistor |
| R9 | Resistor | 47 kΩ | 1 | Q2 bias |
| R10 | Resistor | 330 kΩ | 1 | Q2 bias |
| R12 | Resistor | 360 Ω | 1 | Q2 emitter resistor |
| RC | Resistor | 4.7 kΩ | 1 | Q2 collector resistor |
| R13 | Resistor | 2.2 kΩ | 1 | Output / clipping network |
| R14 | Resistor | 470 Ω | 1 | Output network |
| C1, C2, C3 | Electrolytic capacitor | 2.2 µF | 3 | Signal coupling |
| C4 | Electrolytic capacitor | 47 µF | 1 | Q2 emitter bypass |
| C5 | Electrolytic capacitor | 100 µF | 1 | Supply filter |
| J1, J2 | Mono jack connector | 6.35 mm | 2 | Input and output |
| Power | Battery | 9 V | 1 | Power source |
