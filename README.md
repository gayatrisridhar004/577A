# SRAM Project - USC EE 577A
## Lab 4 Part A
**By: Gayatri Sridhar**

---

### 1. Introduction
In this lab, I designed and verified a **512-bit SRAM array** comprised of 4 banks (8x16 each). In addition, the peripheral circuitry was designed, consisting of:
* **Row Decoder**
* **Precharge Network**
* **Sense Amplifier**
* **Column Mux**
* **Output Registers**

This repository covers the design specifications, critical timing analysis, and simulation reports.

#### Architecture of the 512-bit SRAM
![SRAM Architecture](https://github.com/user-attachments/assets/9176dd98-f4aa-41a0-9045-72b9accd1c4e)

---

### 2. Required Specifications
To ensure stability, the design meets the following noise margin requirements:
* **RSNM:** $\ge 200\text{mV}$
* **WSNM:** $\ge 395\text{mV}$

---

### 3. Block Level Schematics

#### 6T SRAM Cell
![6T SRAM](https://github.com/user-attachments/assets/3bfab9b8-a4bc-4710-90c0-b543d2a1e82d)

#### Sense Amplifier
![Sense Amplifier](https://github.com/user-attachments/assets/e4cd96b4-e0a2-43f1-b63f-2c224c6e3709)

#### Write Datapath Circuit
![Write Datapath](https://github.com/user-attachments/assets/746ce6ae-bc6b-4fb5-b173-d44a0ef37d97)

#### Precharge Circuit
![Precharge Circuit](https://github.com/user-attachments/assets/27fa00a2-7837-4f57-a9b1-143ae7d572f7)

#### Row & Column Peripherals
| Component | Schematic |
| :--- | :--- |
| **Column Mux** | ![Column Mux](https://github.com/user-attachments/assets/e48fa401-6de6-4ba6-a6cb-f69f2bfa0ec1) |
| **Column Decoder** | ![Column Decoder](https://github.com/user-attachments/assets/8222d303-02bc-4b3f-ae12-44125a65abaa) |
| **Row Decoder** | ![Row Decoder](https://github.com/user-attachments/assets/6b298e95-0243-48bb-b524-7aee650787c4) |
| **Output Register** | ![Output Register](https://github.com/user-attachments/assets/d45f41a7-b3b1-46cf-bc5a-148b10abea76) |
