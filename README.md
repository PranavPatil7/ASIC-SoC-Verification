# ASIC SoC ML Accelerator Verification

## 🧠 Project Overview

This project demonstrates end-to-end **ASIC design and functional verification** of a lightweight **Machine Learning (ML) accelerator** integrated into a custom **System-on-Chip (SoC)**. The entire verification flow is implemented using **SystemVerilog**, **UVM (Universal Verification Methodology)**, and **Python** scripting for automation.


---

## 🎯 Objectives

- ✅ Design a simplified ML accelerator (Matrix Multiply Unit)
- ✅ Integrate it into a RISC-V-based SoC (optional extension)
- ✅ Develop a functional SystemVerilog testbench
- ✅ Build a UVM-based verification environment
- ✅ Use Python for test automation and results validation
- ✅ Emulate the real-world design/verification process for Amazon ASICs

---

## 📁 Directory Structure

```
asic-soc-ml-accelerator-verification/
├── rtl/                        # RTL designs (SystemVerilog)
│   └── mma.v                  # Matrix Multiply Accelerator
├── tb/                         # Testbenches
│   └── mma_tb.sv             # Functional testbench
├── scripts/                    # Automation scripts
│   └── run_verilator.py      # Python-based test automation
├── README.md                   # Project overview and setup
├── Makefile                    # Simulation automation
└── .gitignore
```

---

## 🚀 Technologies Used

- **SystemVerilog** – RTL & testbench
- **UVM** – Reusable verification environment (coming next)
- **Python** – Test automation and data validation
- **Verilator** – Open-source simulation
- **RISC-V Core** *(optional)* – Integration with open-source CPU

---

## 💠 How to Run (Coming Soon)

1. **Install Verilator**:
   ```bash
   sudo apt update
   sudo apt install -y verilator
   ```

2. **Run Python Test Generator**:
   ```bash
   python3 scripts/run_verilator.py
   ```

3. **Simulate using Makefile (WIP)**:
   ```bash
   make
   ```

> Detailed simulation and verification instructions will be added with the testbench and UVM flow.

---


---
