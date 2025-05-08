# SUSPENDED BALL CONTROL

This repository supports coursework and demonstrations for the **Suspended Ball Control** project, focusing on modern control techniques using MATLAB and Simulink. The exercises and simulations guide students through the process of modeling, analyzing, and designing controllers for a magnetic levitation (maglev) system.

---

## 📁 Repository Structure

- `Coursework_MATLAB_v2`: Main MALTAB Live Script file with links to associated Simulink models.
- `_sol`: are the separate Simulink files with complete solutions for each stage of the coursework.

---

## 📘 Topics Covered

### 1. **State-Space Modeling**
- Derivation of state-space equations for the suspended ball system.
- Understanding physical modeling of the maglev system using linearized dynamics.

### 2. **Open-Loop Stability Analysis**
- Eigenvalue analysis of the system matrix.
- Assessment of inherent system stability without feedback control.

### 3. **Full-State Feedback Control**
- Pole placement using full-state feedback.
- Controller gain matrix design for desired performance.
- Simulation of closed-loop system response in Simulink.

### 4. **Observer Design Control**
- Design of state observers (estimators) for systems where full state measurement is not available.
- Implementation of combined controller and observer (Luenberger observer).
- Validation using simulations.

---

## 🧑‍🏫 Intended Use

This repository is designed for educational purposes and is part of a university-level control systems course. Students are encouraged to use the `Coursework_MATLAB_v2` for guided exploration, while the `Solutions` folder should be referred to for verification and deeper insights.

---

## 💡 Note

Some Simulink model links in `Coursework_MATLAB_v2` may point to external paths or resources. All necessary solution files are provided separately as `_sol` files for completeness.

---

## 📎 Requirements

- MATLAB 
- Simulink (R2024b or later recommended)
- Control System Toolbox

---

## 🔍 Reference

This project draws on concepts from the Control Tutorials for MATLAB and Simulink (CTMS):

[State-Space Control – Control Tutorials for MATLAB and Simulink (CTMS)](https://ctms.engin.umich.edu/CTMS/index.php?example=Introduction&section=ControlStateSpace)  
© University of Michigan, Carnegie Mellon University, and Detroit Mercy

