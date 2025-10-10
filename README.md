# Cadence_Virtuoso_Implementations
 🧠 Cadence Virtuoso CMOS Circuit Implementations

This repository highlights my **transistor-level CMOS circuit implementations** and simulations designed in **Cadence Virtuoso** using the **GPDK 90 nm** process technology.  
Each circuit was designed from first principles, symbolized, and verified through **transient analysis** to ensure logical correctness, delay, and waveform integrity.

---

## ⚡ Implemented Circuits

- **CMOS Inverter**  
- **NAND Gate**  
- **AND Gate**  
- **OR Gate**  
- **XOR Gate**  
- **Full Adder**  
- **2×1 Multiplexer**  
- **SR Latch**

---

## 🧩 Design Methodology

1. **Transistor-Level Design:** Built each circuit using NMOS and PMOS transistors from **AnalogLib** and **GPDK90**.  
2. **Symbol Creation:** Generated custom symbols for hierarchical integration and reusability.  
3. **Simulation & Verification:**  
   - Performed **transient analysis** using **ADE**  
   - Verified output logic transitions and propagation delay  
   - Analyzed rise/fall times and voltage levels  
4. **Documentation:** Captured schematics, simulation results, and analyzed timing/waveform behavior.

---

## 🧠 Tools & Technologies

- **Cadence Virtuoso** (Schematic Editor, ADE L/XL)  
- **GPDK 90 nm** and **AnalogLib**  
- **CMOS Logic Design**  
- **Transient & DC Analysis**

---

## 📊 Results Overview

All circuits were simulated successfully with correct logic behavior under 90 nm CMOS operation.  
Waveforms confirm expected transitions for each logic gate and sequential circuit.  
*(Screenshots of schematics and simulation results are provided inside respective circuit folders.)*

> ⚠️ *Note:* All designs and analyses are my own academic work.  
> No proprietary Cadence or PDK files are distributed in this repository.

---

## 🪪 License

This repository is shared under the [MIT License](LICENSE).  
Feel free to reference or learn from this work with proper credit.
