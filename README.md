# Capacitive Torque Sensor

A high-precision differential capacitive torque sensor developed by Electronic and Telecommunication Engineering students from the University of Moratuwa.

## Project Overview

This project implements a capacitive torque sensing system that measures mechanical torque through changes in capacitance. As torque is applied to a specially designed shaft, the resulting twist causes a measurable change in capacitance between stationary and rotating plates, which is then processed to provide accurate torque readings.

## Key Features

- High sensitivity capable of detecting torque with precision up to 5 Nm
- Digital output via USB interface
- 1000 samples per second measurement rate
- Temperature compensation
- Compact and durable design
- High resolution (capable of measuring capacitance changes as low as 156 aF)



## Hardware Components

- **Sensing System:** PCAP04 Capacitance-to-Digital Converter (156 aF resolution at 1kHz)
- **Microcontroller:** ATmega32U4 (16MHz, 32KB Flash, 2.5KB SRAM)
- **Dielectric Material:** FR4 Glass Epoxy (Dielectric constant ≈ 4.5)
- **Shaft Material:** Aluminum alloy 6061-T6

## Installation and Setup

### Hardware Setup

1. Assemble the mechanical components according to the design files in `/hardware/mechanical/`
2. Program the ATmega32U4 microcontroller with the firmware
3. Connect the sensor to your computer via USB


## Usage

The sensor provides torque measurements via USB. Data can be accessed through:

1. **Direct serial communication** - Baud rate 115200, 8 data bits, no parity, 1 stop bit
2. **Visualization software** - Shows real-time torque readings and allows data logging
3. **API access** - Library functions to integrate with custom applications

## Calibration

1. Secure the sensor in the calibration fixture
2. Apply known torque values using calibrated weights
3. Run the calibration script to generate a calibration file
4. Load the calibration file when using the sensor

## Performance Specifications

- **Range:** 0-5 Nm
- **Resolution:** 0.01 Nm
- **Accuracy:** ±1% full scale
- **Sampling Rate:** 1000 Hz
- **Operating Temperature:** 0°C to 70°C

## Design Considerations

The final design features:
- Differential measurement for noise reduction
- Optimized shaft design with 0.268 degrees rotation at 1 Nm
- Compact enclosure with mounting feet for stable installation
- Capacitance change of approximately 357.4 fF at full scale

## Team Members

- De Zoysa.A.S.I - 220106D
- Dayananthan.T - 220096T
- Mathujan.S - 220389U
- Pirathishanth.A - 220480P
- Jeyasekara.S.P.R - 220257N
- Sulojan.R - 220626V
- Ananthakumar.T - 220029T
- Ahilakumaran.T - 220017F

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- Department of Electronic and Telecommunication Engineering, University of Moratuwa
- Reference patent: "Differential Capacitive Torque Sensor"
