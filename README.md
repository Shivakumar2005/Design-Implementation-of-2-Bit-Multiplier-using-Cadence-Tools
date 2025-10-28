# Ex No: 06 - Design & Implementation of 2-Bit Multiplier Using Cadence Virtuoso

## Aim
The aim is to design and implement a **2-bit Multiplier** using **Cadence Virtuoso** and verify its functionality through transient analysis simulation.

## Tools Required
### Cadence Virtuoso Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment:
- Open the **Cadence Virtuoso** tool and set up the working library.
- Create a new **schematic cell view** for the **2-bit Multiplier** design.

### 2. Schematic Design:
- Select **NMOS and PMOS transistors** from the library.
- Construct the **2-bit Multiplier circuit** using **AND and ADDER logic gates**.
- Connect the inputs (**A1, A0, B1, B0**) and outputs (**P3, P2, P1, P0**) properly.

### 3. Simulation:
- Check the design for **errors** and proceed with simulation.
- Launch the **Analog Design Environment (ADE)**.
- Perform **transient analysis** to verify the multiplication logic.
- Set up **input stimulus** and analyze the **output waveform**.

## Circuit Diagram

![image](https://github.com/user-attachments/assets/a56c4672-c7a5-44a8-908f-860243dc365d)


## Truth Table for 2-Bit Multiplier

![image](https://github.com/user-attachments/assets/fdb01f7d-60c1-4605-8462-c4dd954c5602)


## Schematic Diagram

### Schematicand Symbol of 2-Input AND Gate:

![WhatsApp Image 2025-10-28 at 17 27 54_6c77a30d](https://github.com/user-attachments/assets/59043e25-7831-4b9e-992e-293e00d22a5f)


![Screenshot 2025-05-10 160505](https://github.com/user-attachments/assets/4031c7a7-7c0f-4397-a936-ac4f90c4f402)

### Schematicand Symbol of 2-Input EX-OR Gate:

![WhatsApp Image 2025-10-28 at 17 38 32_9176705a](https://github.com/user-attachments/assets/73e4a0f2-d93b-43e2-9eb8-494593dd3d29)


![Screenshot 2025-05-10 160523](https://github.com/user-attachments/assets/4230854b-5f8e-43d0-9875-258b457660e3)

### Schematicand Symbol of Half Adder:
![WhatsApp Image 2025-10-28 at 17 44 05_93a72742](https://github.com/user-attachments/assets/fe46b69e-2ee2-4be4-a134-2e04cbb1aaef)


![Screenshot 2025-05-10 161100](https://github.com/user-attachments/assets/bfaa7af0-6785-46e4-b434-87d677af5807)

### Schematic of 2-Bit Multiplier:
![WhatsApp Image 2025-10-28 at 17 21 57_28c9e5ac](https://github.com/user-attachments/assets/f7e65591-d0f9-438d-8538-f730b56eefa8)


## Output
### Transient Analysis Output:
![WhatsApp Image 2025-10-28 at 17 21 35_f1da4e6f](https://github.com/user-attachments/assets/b7421a03-a886-4eee-9da9-260d9486ed31)


![image](https://github.com/user-attachments/assets/55864d90-af08-4836-bc90-4cbba80573f8)


![WhatsApp Image 2025-10-28 at 17 21 15_3dbf519c](https://github.com/user-attachments/assets/94c3a5de-e2bd-4406-8676-c0880bd75976)


Run Time : 200ns

## Results
1. Successfully designed the **2-bit Multiplier** schematic using **Cadence Virtuoso**.
2. Performed **transient analysis**, verifying the correct operation of the **Multiplier**.
3. Observed **correct multiplication behavior** in response to input signals.
