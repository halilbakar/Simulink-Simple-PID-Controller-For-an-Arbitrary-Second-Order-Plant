# PID & Feedforward Controller Design in Simulink

## Overview
This repository demonstrates a **PID controller** integrated with a **feedforward architecture** in MATLAB/Simulink. The project bridges classical **Root Locus analysis** with practical block-diagram modeling, offering an accessible starting point for system control and tuning.

---

## Key Features

* **Simplified Transfer Function:** To keep transfer function derivations straightforward and focus on Simulink mechanics, a uniform gain assumption ($K_p = K_i = K_d$) is applied across the PID controller.
* **Feedforward Architecture:** Combines feedback regulation with feedforward control to improve tracking performance and dynamic response.
* **Root Locus Gain Tuning:** The open-loop root locus plot is integrated alongside the model for fast visual inspection.
* **Optimized Transient Response:** Based on closed-loop pole locations on the root locus, the gain parameter was tuned to **$K = 115$** to minimize overshoot while maintaining system stability.

---

## Getting Started
Explore the included `.slx` file to compare closed-loop step responses, cross-reference root locus pole locations, and experiment with custom gain values.
