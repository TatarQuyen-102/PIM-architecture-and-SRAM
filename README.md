# 🧠 Processing-In-Memory (PIM) Architecture with Embedded SRAM

This project explores a **Processing-In-Memory (PIM)** architecture integrated with **SRAM**, designed and implemented using **Cadence Virtuoso**. The goal is to minimize data movement between memory and processing units, significantly improving performance and energy efficiency for data-intensive applications.

---

## 📐 Block Diagram of the PIM Architecture

<img src="https://github.com/user-attachments/assets/f95a754e-d750-416a-a7aa-e865b010f369" width="450"/>

The system integrates compute units directly within or near the memory arrays to reduce latency and energy cost associated with memory access.

---

## 🔧 SRAM-Based Compute Units

### 📦 SRAM Cell Integration
<img src="https://github.com/user-attachments/assets/35605a97-dcb3-4b2a-a237-a8f9ddab4b95" width="400"/>

- Embedded SRAM cells serve as both storage and computational logic elements.
- Logic operations such as AND, OR, and XOR are supported directly within memory.

---

### 🧲 Peripheral Logic + Wordline Driver
<img src="https://github.com/user-attachments/assets/ebf2d3e3-6f28-41f6-b5c4-01e24ea814a8" width="400"/>

- Peripheral circuits (e.g., wordline drivers, sense amplifiers, decoders) are enhanced to support in-memory computing.
- Bit-line manipulation enables data-parallel operations.

---

## 💡 Key Features

- ✅ **In-Memory Logic Operations**
- ✅ **Reduced Data Movement**
- ✅ **Low Latency Memory Access**
- ✅ **Custom Peripheral Circuitry**
- ✅ **Scalable to Larger SRAM Arrays**

---

## 🧪 Tools & Technology

- **Design Environment**: Cadence Virtuoso
- **Simulation**: Spectre (transistor-level)
- **Technology Node**: [e.g., 65nm / 45nm / 28nm — *(update accordingly)*]
- **Memory Type**: 6T SRAM Cell with modified bit-line access

---

## 📂 Project Structure

```bash
.
├── layout/               # Virtuoso layout files (.gds, .oa)
├── schematic/            # Schematic cells (in Cadence)
├── sim/                  # Spectre simulation setup and results
├── docs/                 # Block diagrams, papers, and documentation
└── README.md             # Project overview

