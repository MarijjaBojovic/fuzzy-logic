# 🎛️ Intuitive Fuzzy Logic Control System

This project features the design and implementation of an **Intuitive Fuzzy Logic Controller** developed to stabilize a dynamic system. The controller was designed based on expert knowledge and intuitive linguistic rules, then simulated and verified using **MATLAB & Simulink**.

---

## 🚀 Project Overview

### 1. 🧠 Fuzzy Controller Design
* **Intuitive Logic:** Built using a Mamdani-type inference system, where control rules were derived intuitively to mimic human-like decision-making.
* **Fuzzification:** Defined membership functions for error and change-of-error inputs (e.g., Negative Big, Zero, Positive Big).
* **Rule Base:** Developed a comprehensive set of "IF-THEN" rules to ensure smooth system response and stability.

### 2. 💻 Simulink Implementation
* **System Modeling:** Integrated the Fuzzy Logic Controller block with a plant model in the Simulink environment.
* **Closed-Loop Stability:** Created a feedback loop system to test the controller's ability to minimize steady-state error and handle disturbances.
* **Performance Analysis:** Used Scope blocks to monitor real-time stabilization and transient response.

---

## 🛠️ Tools Used
* **MATLAB:** For fuzzy inference system (FIS) tuning and script management.
* **Simulink:** For block-diagram modeling and dynamic system simulation.
* **Fuzzy Logic Toolbox:** To define membership functions and inference engines.
