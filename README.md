# SRAM Project - USC EE 577 A
## Lab 4 part A
### By - Gayatri Sridhar
1) Introduction: In this lab I designed and verification of a 512-bit SRAM array which is comprised of 4 banks (8x16 each). In addition the peripheral circuitry- consisting row decoder, precharge network, Sense amplifier, Column mux and output registers - were also designed. This repository covers the design details specifucations, critical timing analysis and simulation reports.
The following image gives the architecture of the 512-bit SRAM:
   <img width="502" height="256" alt="Screenshot 2026-01-19 at 11 19 30 PM" src="https://github.com/user-attachments/assets/9176dd98-f4aa-41a0-9045-72b9accd1c4e" />

Required specifications:
RSNM>=200mv and WSNM>=395mV

2) Block Level Schematics
   6T SRAM:
   <img width="689" height="305" alt="Screenshot 2026-01-19 at 11 29 14 PM" src="https://github.com/user-attachments/assets/3bfab9b8-a4bc-4710-90c0-b543d2a1e82d" />

   Sense Amplifier:
   <img width="615" height="400" alt="Screenshot 2026-01-19 at 11 30 52 PM" src="https://github.com/user-attachments/assets/e4cd96b4-e0a2-43f1-b63f-2c224c6e3709" />

   Write Datapath Circuit:
   <img width="694" height="320" alt="Screenshot 2026-01-19 at 11 31 20 PM" src="https://github.com/user-attachments/assets/746ce6ae-bc6b-4fb5-b173-d44a0ef37d97" />

   Precharge Circuit:
   <img width="677" height="401" alt="Screenshot 2026-01-19 at 11 31 33 PM" src="https://github.com/user-attachments/assets/27fa00a2-7837-4f57-a9b1-143ae7d572f7" />

   Column Mux:
   <img width="677" height="321" alt="Screenshot 2026-01-19 at 11 39 47 PM" src="https://github.com/user-attachments/assets/e48fa401-6de6-4ba6-a6cb-f69f2bfa0ec1" />

   Column Decoder:
   <img width="677" height="397" alt="Screenshot 2026-01-19 at 11 40 44 PM" src="https://github.com/user-attachments/assets/8222d303-02bc-4b3f-ae12-44125a65abaa" />

   Row Decoder:
   <img width="677" height="353" alt="Screenshot 2026-01-19 at 11 40 54 PM" src="https://github.com/user-attachments/assets/6b298e95-0243-48bb-b524-7aee650787c4" />

   SRAM 4 Column Mux:
   <img width="664" height="351" alt="Screenshot 2026-01-19 at 11 41 56 PM" src="https://github.com/user-attachments/assets/54330998-02cc-4640-a8a6-b0b30e012b0c" />


   Output Register:
   <img width="670" height="304" alt="Screenshot 2026-01-19 at 11 49 08 PM" src="https://github.com/user-attachments/assets/d45f41a7-b3b1-46cf-bc5a-148b10abea76" />

   SRAM Decoder RW Schematic:
   <img width="664" height="351" alt="Screenshot 2026-01-19 at 11 41 56 PM" src="https://github.com/user-attachments/assets/df70dd13-60e0-4986-a7ca-f8d9bec860f5" />

