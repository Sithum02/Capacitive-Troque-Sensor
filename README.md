# Capacitive Torque Sensor

## 🌀 Overview

The project is a low-cost, high-sensitivity capacitive torque sensor capable of converting mechanical torque into a digital signal using a custom-designed sensing mechanism, a capacitance-to-digital converter (PCAP04), and a USB-enabled microcontroller (ATmega32U4).

## 🧠 Functionality

- Measures torque via changes in capacitance caused by shaft deformation.
- High-resolution digital readout through SPI communication.
- Data is transmitted over USB and visualized on a PC.


## 🔧 Hardware Specs

- **Capacitance-to-Digital Converter:** PCAP04
- **Microcontroller:** ATmega32U4
- **Dielectric Material:** FR4 (Epoxy Glass)
- **Shaft Material:** Aluminum Alloy 6061-T6
- **Sampling Rate:** 1kHz
- **Capacitance Range:** ±50pF, Resolution: 156aF
- **Enclosure:** Semi-cylindrical, compact and mountable

## 🛠️ Build Instructions

1. **PCB Fabrication:**
   - Use provided 4-layer Altium PCB files.
   - Ensure differential pair routing for USB signals.

2. **Mechanical Assembly:**
   - Fabricate shaft and housing using provided SolidWorks files.
   - Mount disks with precision alignment for capacitance measurement.

3. **Firmware Flashing:**
   - Compile `main.c` using Microchip Studio or `avr-gcc`.
   - Flash to ATmega32U4 using USB bootloader or JTAG.

4. **PC Interface:**
   - Connect device via USB.
   - Use included PC software to read and visualize torque values in real-time.

## 🧪 Testing Features

- JTAG Interface for MCU debugging and boundary scan.
- USB signal integrity test points.
- Differential capacitance measurement validation.

## 📊 Production Cost Estimate

- Detailed Bill of Materials (BOM) provided.
- Includes alternatives for key components.
- Approximate cost for one unit documented.

## 💡 Key Features

- High sensitivity torque detection via differential capacitance
- Compact and lightweight mechanical design
- Real-time torque data streaming over USB
- Software-calibrated output using polynomial regression
- Low noise, high-resolution digital conversion (PCAP04)

## 👥 Team Members

- De Zoysa A.S.I. - 220106D  
- Dayananthan T. - 220096T  
- Mathujan S. - 220389U  
- Pirathishanth A. - 220480P  
- Jeyasekara S.P.R. - 220257N  
- Sulojan R. - 220626V  
- Ananthakumar T. - 220029T  
- Ahilakumaran T. - 220017F

## 📚 References

- US Patent: [US10267690B2 - Differential Capacitive Torque Sensor](https://patents.google.com/patent/US10267690B2/en)
- Microchip ATmega32U4 Datasheet
- PCAP04 Capacitance-to-Digital Converter Datasheet

## 🛡️ License

This project is for educational use only. For commercial use or licensing inquiries, please contact the project supervisor or the Department of Electronic and Telecommunication Engineering, University of Moratuwa.

---

> Made with 💡 and 💻 at the University of Moratuwa


