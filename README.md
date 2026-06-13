# PID Controller Design and Simulation using MATLAB/Simulink

## Overview

This project demonstrates the design, implementation, and performance analysis of a PID (Proportional-Integral-Derivative) Controller using MATLAB/Simulink. The controller is used to improve the dynamic response of a system by reducing steady-state error, minimizing overshoot, and achieving faster settling time.

## Objectives

* Design a PID controller for a dynamic system.
* Analyze system performance with and without PID control.
* Tune controller parameters (Kp, Ki, Kd) to achieve desired performance.
* Evaluate transient and steady-state response characteristics.

## Features

* MATLAB/Simulink-based simulation model.
* Adjustable PID controller parameters.
* Step response analysis.
* Performance comparison before and after controller implementation.
* Visualization of system behavior through simulation graphs.

## Tools and Technologies

* MATLAB
* Simulink
* PID Controller
* Control System Toolbox

## Project Structure

```
├── PID_Controller_Model.slx
├── Simulation_Results/
├── Documentation/
└── README.md
```

## Working Principle

The PID controller continuously calculates the error between the desired setpoint and the actual output. Based on this error:

* Proportional (P) term reduces present error.
* Integral (I) term eliminates accumulated past error.
* Derivative (D) term predicts future error and improves stability.

The controller output is given by:

u(t) = Kp·e(t) + Ki∫e(t)dt + Kd(de(t)/dt)

## Simulation Results

The simulation demonstrates:

* Improved system stability.
* Reduced steady-state error.
* Faster settling time.
* Controlled overshoot and oscillations.

## How to Run

1. Open MATLAB.
2. Open the Simulink model file (`.slx`).
3. Configure the PID gains if required.
4. Run the simulation.
5. Observe the response graphs and analyze performance.

## Learning Outcomes

* Understanding PID controller operation.
* MATLAB/Simulink modeling and simulation.
* Control system performance analysis.
* PID tuning techniques and optimization.

## Author

**Mohit Pikhan**
Instrumentation and Control Engineering
