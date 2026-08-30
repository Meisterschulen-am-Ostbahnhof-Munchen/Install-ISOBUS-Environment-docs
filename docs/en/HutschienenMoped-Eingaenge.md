# DIN Rail Moped Inputs
## Differentiation of Limit Switches for Pneumatic Cylinders:
[https://www.ifm.com/at/de/shared/produkte/zylindersensoren/technologie](https://www.ifm.com/at/de/shared/produkte/zylindersensoren/technologie)
### Reed Switch
A reed switch is an electrical switching element consisting of two ferromagnetic contacts inside a hermetically sealed glass tube. These contacts are held apart by a thin, flexible glass rod coated with a special metal alloy.
The main characteristics of a reed switch are:

1. Magnetic Activation: A reed switch is activated by a magnetic field. When the field is strong enough, the contacts move and close an electrical circuit.

2. Small Size: Reed switches are very small and can be installed in confined spaces.

3. High Switching Speed: Due to their small size, reed switches can switch very quickly, making them ideal for applications such as circuits and sensors.

4. High Reliability: Because reed switches are hermetically sealed, they are protected against moisture, dust, and other environmental influences, which increases their lifespan and reliability.

5. Low Power Consumption: Reed switches require very little power to switch, making them ideal for battery-powered applications.

6. High Sensitivity: Reed switches can respond to even very weak magnetic fields, making them ideal for applications such as magnetic field sensors and ammeters.

[https://de.wikipedia.org/wiki/Reedschalter](https://de.wikipedia.org/wiki/Reedschalter)

Reed Switch Characteristics:

- Normally Open: always 2-wire technology
- Normally Closed: always 2-wire technology
- Changeover (rare): 3-wire technology
- Only the maximum voltage is specified in the datasheet
- Current Direction: irrelevant
- Ground Terminal: not present
- Usually no LED (except for special designs)
- Not short-circuit protected!!!

[https://www.ifm.com/de/de/product/MR0100](https://www.ifm.com/de/de/product/MR0100)

### Semiconductor Magnetic Sensors

[https://de.wikipedia.org/wiki/Magnetoresistiver_Effekt](https://de.wikipedia.org/wiki/Magnetoresistiver_Effekt)

Always Specified: e.g., 5...36 V DC

- Minimum and maximum voltage specified!!!

- Normally open (NO) contact: usually 3-wire technology

- Normally closed (NC) contact: usually 3-wire technology
- Changeover contact: 4-wire
- Current direction: alternating, see PNP/NPN, L+ L-
- Ground terminal: not present
- Usually no LED (except for special designs)
- Modern designs are short-circuit protected, cannot burn out

Example: [https://www.ifm.com/de/de/product/MK5214](https://www.ifm.com/de/de/product/MK5214) (short-circuit proof; overload proof)

#### PNP Sensor

![](https://user-images.githubusercontent.com/69573151/223118993-3d7325eb-8fa6-451e-b90b-1ac3028e7764.png)

Source: [https://www.ifm.com/de/de/product/MK5140](https://www.ifm.com/de/de/product/MK5140)

#### NPN Sensor

![](https://user-images.githubusercontent.com/69573151/223119312-1da2bd00-5cbf-4606-bea7-73da028c0ae0.png)

Source: [https://www.ifm.com/de/de/product/MK5309](https://www.ifm.com/de/de/product/MK5309)

#### AMR Cell

An AMR cell (Anisotropic Magnetoresistive Cell) is a type of An AMR cell is a magnetoresistive cell used in the semiconductor and magnet industries. It consists of a thin layer system of ferromagnetic and non-magnetic layers deposited on a silicon substrate.

The key characteristics of an AMR cell are:

1. Magnetic Sensitivity: The AMR cell is highly sensitive to magnetic fields and can detect even minute magnetic changes.

2. Low Power Consumption: The AMR cell requires very little power to operate.

3. High Accuracy: The AMR cell can perform highly precise measurements and is therefore ideal for applications requiring high accuracy, such as magnetic field sensing.

4. High Speed: The AMR cell can respond very quickly to changes in the magnetic field and is therefore ideal for applications requiring rapid measurements, such as data processing.

5. Low Cost: The AMR cell is relatively inexpensive and easy to manufacture, making it suitable for a wide range of applications.

Overall, the AMR cell is a very versatile component that can be used in many different applications, from magnetic field sensing to data processing and many other areas.

#### GMR Cell

A GMR cell (Giant Magnetoresistive Cell) is a type of magnetoresistive cell used in the semiconductor and magnet industries. The GMR cell consists of several thin layers of ferromagnetic and non-magnetic materials deposited in a layered structure on a substrate.

The most important characteristics of a GMR cell are:

1. High sensitivity: The GMR cell is very sensitive to magnetic fields and can detect very small changes.

2. High accuracy: The GMR cell can perform very precise measurements and is therefore ideal for applications where high accuracy is required, such as magnetic field sensing.

3. Low power consumption: The GMR cell requires very little power to operate.

4. High Speed: The GMR cell can react very quickly to changes in the magnetic field and is therefore ideal for applications requiring fast measurements, such as in data processing.

5. High Temperature Stability: The GMR cell is very temperature stable and can be used even at high temperatures.

6. Low Cost: The GMR cell is relatively inexpensive and easy to manufacture, making it suitable for a wide variety of applications.

Overall, the GMR cell is a very versatile component that can be used in many different applications, from magnetic field sensing to data processing and many other areas.

[https://www.ifm.com/de/de/product/MK5117](https://www.ifm.com/de/de/product/MK5117)

## Connecting the Limit Switch to the Input

![](https://cdn.shopify.com/s/files/1/0056/7689/2250/products/7_da00f974-6952-4ad6-9f08-beaab6c888d5_1200x1200.jpg?v=1655692121)

M5 Stack:

Input Voltage at the Pin:

3.3V

Voltage from the Sensor:

5V

Voltage Divider:

![](https://user-images.githubusercontent.com/69573151/223125789-46ed37a7-2fca-48a4-8d62-4cc9b57bb5f4.png)

[https://www.digikey.de/de/resources/conversion-calculators/conversion-calculator-voltage-divider](https://www.digikey.de/de/resources/conversion-calculators/conversion-calculator-voltage-divider)

In Practice:

1. Resistor 1800 Ohm

2. Resistor 3300 Ohm

Because:

[https://www.electronicsplanet.ch/Widerstand/Widerstandsreihe-E24.htm](https://www.electronicsplanet.ch/Widerstand/Widerstandsreihe-E24.htm)

]
![](https://user-images.githubusercontent.com/69573151/223126038-5d9b7d5e-2608-4ebf-8e39-4226a0df0cd0.png)

## Grove System

[https://www.seeedstudio.com/category/Grove-c-1003.html](https://www.seeedstudio.com/category/Grove-c-1003.html)

<https://exp-tech.de/search?type=product&q=grove>

[https://www.distrelec.de/search?q=grove](https://www.distrelec.de/search?q=grove)

## Series Connection of Limit Switches

[https://www.baumer.com/de/de/service-support/inbetriebnahme-montage/inbetriebnahme-und-montage-von-induktiven-sensoren/a/Know-how_Mounting_Inductive-sensors](https://www.baumer.com/de/de/service-support/inbetriebnahme-montage/inbetriebnahme-und-montage-von-induktiven-sensoren/a/Know-how_Mounting_Inductive-sensors)

## Button Boards

[https://github.com/Meisterschulen-am-Ostbahnhof-Munchen/ButtonBoards](https://github.com/Meisterschulen-am-Ostbahnhof-Munchen/ButtonBoards)

Multiplexers

---

### 🌐 Related Topic Subpages on ms-muc-docs.de
- [🌐 Total Resistance in Series & Parallel Circuits on ms-muc-docs.de](https://www.ms-muc-docs.de/elektrotechnik/elektrik/widerstand/widerstand-theorie/gesamtwiderstand-reihen-parallelschaltung/)
- [🌐 Loaded & Unloaded Voltage Dividers on ms-muc-docs.de](https://www.ms-muc-docs.de/elektrotechnik/elektrik/widerstand/widerstand-theorie/spannungsteiler/)
- [🌐 Bipolar transistor fundamentals at ms-muc-docs.de](https://www.ms-muc-docs.de/elektrotechnik/elektronik-i/bipolartransistor/bipolarer-transistor/)

