# LED Chaser PCB Design

This repository contains the Altium Designer project files for a simple **LED Chaser Circuit**. The circuit sequentially blinks a series of LEDs using a counter IC, commonly used for learning PCB design, digital logic, and soldering.

---

## 🔧 Project Description

The LED Chaser circuit is designed to sequentially light up 10 LEDs in a "running" pattern using a CD4017 Decade Counter and a 555 Timer-based pulse generator.

---

## ⚙️ Features

- CD4017 Decade Counter IC
- NE555 Timer in Astable Mode
- 8 LED Outputs with Current-Limiting Resistors
- SMD or Through-Hole Component Support
- 5V Input Supply (Battery or USB)

---

## 📁 Files Included

| File/Folder                          | Description                            |
|-------------------------------------|----------------------------------------|
| `LEDChaser.PrjPcb`                  | Main Altium project file               |
| `LEDChaser.SchDoc`                  | Schematic design                       |
| `LEDChaser.PcbDoc`                  | PCB layout                             |
| `CAMtastic1`                        | CAM output or previews                 |
| `README.md`                         | This documentation file                |

---

## 🖥️ Preview

_Schematic View_

![image](https://github.com/user-attachments/assets/f3615c55-e744-4c43-9ffd-a6442a33de29)


_PCB Layout_

![image](https://github.com/user-attachments/assets/57d519cc-0f52-4b09-b598-fe135a5db950)



---


## 📦 Bill of Materials (BOM)

| Component | Value/Part         | Quantity |
|-----------|--------------------|----------|
| IC1       | NE555 Timer        | 1        |
| IC2       | CD4017 Decade Counter | 1     |
| R1, R2    | 10kΩ               | 2        |
| C1        | 10µF               | 1        |
| LEDs      | Red/Green/Blue     | 8        |
| R3–R10    | 330Ω               | 8        |
| Power Jack| 5V DC Barrel/USB   | 1        |

---

## 🧾 License

This project is open-source under the [MIT License](LICENSE).

---

## 🙌 Credits

Designed by Senthilkumaran K, using **Altium Designer**  
Inspired by classic digital electronics training circuits.

---

