# 🌡️ Digital Thermometer Using 8051 Microcontroller

This project is a digital thermometer built using the **8051 microcontroller**, **LM35 temperature sensor**, and **ADC0804**. It displays real-time temperature readings on a **16x2 LCD** using embedded C. Developed as part of the ECT206: Computer Architecture and Microcontroller course.

---

## 💡 How It Works

1. **LM35** outputs an analog voltage proportional to the temperature (10mV/°C).
2. **ADC0804** converts this analog signal to an 8-bit digital value.
3. **8051 Microcontroller** reads this digital data and processes it to calculate temperature.
4. The final temperature is shown on a **16x2 LCD** in °C.

---

## ⚙️ Requirements

### Hardware:
- 8051 Microcontroller (AT89C51/AT89S51)
- LM35 Temperature Sensor
- ADC0804
- 16x2 LCD Display
- 11.0592 MHz Crystal Oscillator
- Voltage Regulator (7805)
- Capacitors, Resistors, Potentiometer, Jumper wires

### Software:
- **Keil µVision IDE** (Embedded C coding)
- **Proteus Design Suite** (Simulation)
- Optional: **Flash Magic** (for flashing HEX file to real hardware)

---

## 🚀 How to Use

1. Open the simulation file in **Proteus**.
2. Run the simulation.
3. Watch the **LCD** display the current ambient temperature.
4. You can adjust temperature input manually in simulation or test it with real hardware using LM35.

---

## 📌 Notes

- LM35 provides 10mV per °C. So, 250mV → 25°C.
- ADC0804 gives 8-bit output (0–255). Scaling and conversion logic is handled in the microcontroller code.
- Accuracy depends on precise reference voltage and component quality.

---

## 📜 License

This project is open-source and intended for educational and academic purposes.  
You’re welcome to fork, modify, and build upon it.

---

## 🙌 Acknowledgements

Created for academic learning and hands-on microcontroller experience using 8051.

