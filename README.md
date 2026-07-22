# PID & Feedforward Controller Design in Simulink

## Overview
This repository demonstrates a **PID controller** integrated with a **feedforward architecture** in MATLAB/Simulink. The primary goal is to gain familiarity with Simulink block diagrams and bridge classical **Root Locus analysis** with practical system modeling.

---

## Key Features

* **Simplified Equal-Gain Assumption:** To keep algebraic derivations simple and make transfer function analysis easy to manage in Simulink, all PID gains were assumed equal ($K_p = K_i = K_d$). While this assumption holds no direct physical interpretation in this system's context, it streamlines the mathematical modeling so the focus remains on learning Simulink mechanics.
* **Feedforward Architecture:** Integrates a feedforward path alongside the feedback loop to improve reference tracking and overall transient response.
* **Root Locus Gain Tuning:** The open-loop root locus plot is embedded directly into the Simulink file to allow quick gain matching and visual inspection.
* **Optimized Transient Response:** By inspecting closed-loop pole locations on the root locus, the gain parameter was set to **$K = 115$** to achieve a smaller overshoot while keeping the system stable.

---

## Getting Started
Open the included `.slx` file in MATLAB/Simulink to inspect the block diagram layout, check the root locus gain matching, and run step-response simulations.
