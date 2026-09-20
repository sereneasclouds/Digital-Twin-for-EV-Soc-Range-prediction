# EV Virtual Prototyping — Simulink Full-Stack Drivetrain and Digital Twin for SoC & Range Prediction

A **MATLAB/Simulink-based Electric Vehicle (EV) virtual prototyping and
digital-twin project** developed to model an integrated electric drivetrain,
simulate vehicle behaviour, and predict battery State of Charge (SoC) and
driving range.

The project integrates **vehicle dynamics, electric motor modelling,
H-bridge control, closed-loop speed control, battery SoC estimation, and
range prediction** within a unified Simulink simulation environment.

The objective is to use simulation-based development to evaluate EV
drivetrain behaviour and energy consumption while reducing the time and cost
associated with early-stage physical prototyping.

---

## Project Overview

The project develops a full-stack EV drivetrain model in **MATLAB/Simulink**
that connects the electrical, mechanical, control, and battery subsystems of
an electric vehicle.

The simulation includes:

- Vehicle longitudinal dynamics
- Vehicle mass and tyre behaviour
- Aerodynamic drag
- Rolling resistance
- DC motor modelling
- H-bridge motor drive
- PWM-based motor control
- Closed-loop speed control
- Drive-cycle simulation
- Battery current modelling
- State-of-Charge (SoC) estimation
- Vehicle distance calculation
- Driving-range prediction

The integrated model enables vehicle-level performance and energy
consumption to be studied within a single virtual environment.

---

## Project Objectives

The main objectives of the project are to:

- Develop an integrated EV drivetrain model using **MATLAB/Simulink**.
- Combine electrical, mechanical, and control-domain models within a
  unified simulation.
- Simulate vehicle behaviour under a defined drive cycle.
- Model the interaction between the electric motor, H-bridge, and vehicle
  dynamics.
- Implement closed-loop vehicle speed control.
- Estimate battery State of Charge using Coulomb counting.
- Calculate travelled distance from vehicle velocity.
- Predict baseline driving range from simulated SoC consumption.
- Explore EV drivetrain behaviour through virtual prototyping.
- Enable faster design iteration before physical prototype development.
- Reduce the time and cost associated with early-stage physical testing.

---

## Digital Twin / Virtual Prototyping Concept

The project uses **MATLAB/Simulink as a virtual representation of an EV
drivetrain**, allowing different vehicle, drivetrain, control, and operating
conditions to be evaluated through simulation.

```text
              EV VIRTUAL PROTOTYPE / DIGITAL TWIN
                              │
                              ▼
                     Drive Cycle Input
                              │
                              ▼
                    Speed Control System
                              │
                              ▼
                       H-Bridge + PWM
                              │
                              ▼
                         DC Motor
                              │
                              ▼
                    Vehicle Dynamics
                              │
                    ┌─────────┴─────────┐
                    ▼                   ▼
              Vehicle Speed       Battery Current
                    │                   │
                    ▼                   ▼
              Distance Travelled       SoC
                    │                   │
                    └─────────┬─────────┘
                              ▼
                       Range Prediction
