## Experiment 7 (a): Analog to Digital Converter (ADC) using Proteus
## Aim
To design and simulate an Analog to Digital Converter (ADC) circuit using Proteus and observe the conversion of an analog input voltage into its equivalent digital output.
## Apparatus / Software Required
•	Proteus Design Suite
•	ADC IC (ADC0804)
•	Resistors
•	Capacitor
•	Potentiometer (for analog input)
•	Clock components
•	LED display / Logic probe
•	Power supply (5V)
## Theory
An Analog to Digital Converter (ADC) converts a continuous analog signal into a digital representation. ADCs are widely used in digital systems where analog signals from sensors need to be processed by microcontrollers or computers.
The ADC0804 is an 8-bit ADC that uses the successive approximation technique for conversion. It converts the analog input voltage into an equivalent 8-bit binary number.
Important Features
•	Resolution: 8-bit
•	Input voltage range: 0–5 V
•	Conversion method: Successive approximation
•	Output: Digital binary (D0–D7)
The digital output is proportional to the input analog voltage.
## Circuit Diagram

Design the circuit in Proteus using ADC0804 with:
•	Analog input from potentiometer
•	Clock using resistor and capacitor
•	Output connected to LEDs or logic probes
## Procedure
1.	Open Proteus Design Suite.
2.	Select the following components from the library:
o	ADC0804
o	Resistor
o	Capacitor
o	Potentiometer
o	LEDs
3.	Connect the analog input pin (VIN+) to the potentiometer.
4.	Connect VIN− to ground.
5.	Create the clock using resistor and capacitor between CLK pins.
6.	Connect output pins D0–D7 to LEDs.
7.	Apply 5V supply to the ADC.
8.	Run the simulation.
9.	Vary the potentiometer and observe the digital output.

## Tabulation

## Result
The Analog to Digital Converter circuit was successfully designed and simulated in Proteus, and the analog input voltage was converted into the corresponding digital output.
