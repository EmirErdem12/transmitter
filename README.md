# Custom Universal RC Transmitter 🎮

<img width="365" height="268" alt="image" src="https://github.com/user-attachments/assets/e6b004d2-f850-4e3f-bc6f-1e7b61822c17" />

## 📌 About the Project
This project is a custom-designed, 3D-printable universal radio controller (transmitter) engineered for RC vehicles, drones, and robotic applications. The system features a highly modular internal architecture, allowing it to be powered by either an Arduino or a PIC16F887 microcontroller depending on the user's requirements.

## ⚙️ Technologies & Tools
* **CAD Design:** SolidWorks
* **Manufacturing:** Creality Ender 3 V3 CoreXZ (FDM 3D Printing)
* **Microcontroller (Modular):** Arduino / PIC16F887
* **Power Supply:** 2x 18650 Li-ion Batteries
* **Interface / IO:** Dual Analog Joysticks, 16x2 I2C LCD Display, Rotary Encoder, Main Power Switch

## 🛠️ Mechanical Enclosure Design (CAD)
The ergonomic enclosure was modeled in SolidWorks, consisting of upper and lower shells secured by corner screws. Precise cutouts and tolerances were calculated for the joysticks, LCD screen, switches, and a bottom port for programming/charging access.

<img width="504" height="334" alt="image" src="https://github.com/user-attachments/assets/e206aca1-c6b0-42da-a279-8cd117823226" />

## ⚡ Electronics & Modularity
The core advantage of this transmitter is its flexible electronic design. It operates on a robust power supply using two 18650 cells. The internal mounting points are designed to accommodate different development boards, giving the developer the freedom to write firmware in C/C++ (Arduino) or Assembly/C (PIC).

<img width="606" height="422" alt="image" src="https://github.com/user-attachments/assets/138dc693-734d-488d-887e-2bbe1e173e20" />

## 🖨️ Assembly & Prototyping
The outer shells were printed using PLA/PETG. The final assembly involved integrating the joysticks, soldering the communication lines to the selected microcontroller, and routing the battery management system.

## 📂 Repository Structure
* `CAD_Files/` : SolidWorks files (.sldprt, .sldasm) and .STEP files
* `STL_Files/` : 3D printable models (.stl)
* `Code/` : Firmware examples for Joystick data transmission (Arduino / PIC)
