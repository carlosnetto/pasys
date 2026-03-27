# Pasys: A Pedagogical OS Development Suite

**Pasys** is an educational project designed for university-level Operating Systems courses. Unlike production compilers focused on raw performance, Pasys is built for **transparency and education**, allowing students to explore the deep orchestration between software and hardware.

The suite provides a complete "vertical stack"—from a Pascal compiler to a virtual hardware executor and a fully functional minimalist operating system.

---

## 🏗️ The Ecosystem

The project is composed of three core pillars:

| Component | Description | Educational Focus |
| :--- | :--- | :--- |
| **Pasys** | The Pascal Compiler | Translates source code into specialized P-Code. |
| **SIM505** | The VM & Executor | Simulates a virtual machine and hardware (CPU, Memory, I/O). |
| **SOFIA** | The Operating System | A complete OS implementation in just **2,000 lines of code**. |

---

## 🎓 Learning Objectives

Pasys and its components are specifically designed to demonstrate:

* **Process & Thread Management:** How the OS schedules and switches contexts.
* **Hardware Interrupts:** Handling external signals and asynchronous events.
* **DMA (Direct Memory Access):** Understanding data transfer without CPU intervention.
* **Hardware Orchestration:** How a kernel manages the relationship between code and physical (or virtual) components.

---

## 🚀 Getting Started

### 1. The Compiler (Pasys)
Use Pasys to compile your Pascal source files into P-Code. The compiler is designed to be readable so students can understand how high-level constructs map to machine-level logic.

### 2. The Virtual Machine (SIM505)
Run your compiled code on **SIM505**. This isn't just an interpreter; it simulates the hardware environment, allowing you to trigger interrupts and manage virtual DMA controllers.

### 3. Exploring SOFIA
**SOFIA** serves as the ultimate reference. In only 2,000 lines, it implements a full operating system. It is small enough to be read and understood in a single semester, yet powerful enough to demonstrate complex kernel concepts.

---

## 📂 Examples
The repository includes several small examples that are simpler than SOFIA. These are perfect for:
* Testing basic P-Code execution.
* Learning how to write simple drivers for SIM505 hardware.
* Understanding basic concurrency primitives.

---

## 🤝 Credits

This project is the result of the vision and work of:

* **[Francisco Barguil](https://www.linkedin.com/in/franciscobarguil/)**
* **[Fernando Vanini](https://www.linkedin.com/in/fernando-vanini-257354/)**
* **[Rogerio Drummond](https://www.linkedin.com/in/rog%C3%A9rio-drummond-94a5a97/)**

---

## 📄 License
[Insert your chosen license here, e.g., MIT, GPLv3]
