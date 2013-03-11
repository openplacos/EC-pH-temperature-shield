EC, pH and temperature shield for arduino.

## Schematic & Simulations
### pH Sensor

The pH sensor is inspired from phDuino.
It is composed by an amplifier and a 2nd order low-pass filter (Rauch)
The amplifier is designed to span the input range of a typical pH probe (-400 -> 400 mV) to the input range of an arduino ADC (0 -> 5V). pH = 0 gives 2.5V. 

[![CircuitLab Schematic ytznut](https://www.circuitlab.com/circuit/ytznut/screenshot/540x405/)](https://www.circuitlab.com/circuit/ytznut/ph-sensor/)

### EC Sensor
The EC sensor is composed by 3 main structures:
* A 2nd order low pass-filter (Rauch) in order to convert the PWM input into a +-200mV sin wave.
* A trans-impedance amplifier
* A crete detector.

[![CircuitLab Schematic tbs682](https://www.circuitlab.com/circuit/tbs682/screenshot/540x405/)](https://www.circuitlab.com/circuit/tbs682/ec-sensor/)

### Temperature Sensor
The temperature sensor is just a 1-wire temperature sensor (DS18B20).
