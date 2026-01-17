# STM32F103CBT6 Development Board Design

This project contains the full hardware design files for a custom development board based on the **STM32F103CBT6** microcontroller. It is designed to be a compact and versatile platform for embedded system development, featuring enhanced memory and optimized peripheral access.

---

## 🛠 Technical Specifications

* **Microcontroller:** STM32F103CBT6 (ARM® Cortex®-M3)
* **Core Specs:** 72 MHz frequency, 128 KB Flash memory, 20 KB SRAM.
* **Pin Count:** 48-pin LQFP package.
* **Design Tool:** Altium Designer
* **Interfaces:** SWD for debugging, USB-C/Micro-USB for connectivity, and breakout headers for all GPIOs.

---

## 🚀 Engineering Highlights

* **Memory Advantage:** Utilizing the "CBT" variant provides 128 KB of Flash, double the capacity of standard entry-level boards, allowing for more complex firmware architectures.
* **Power & Signal Integrity:** Decoupling capacitors are placed in close proximity to the MCU power pins to minimize noise.
* **Clock Design:** Optimized trace routing for the 8MHz and 32.768kHz crystal oscillators to ensure timing stability.
* **Compact Layout:** A focused 2-layer PCB design with dedicated ground planes for improved EMI performance.

---

## 📁 Project Structure

* **/Schematics:** Schematic diagrams including power regulation and MCU peripherals.
* **/PCB Layout:** Optimized 2-layer PCB design files.
* **/Manufacturing:** Gerber and NC Drill files ready for fabrication.


