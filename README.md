# Peregrine Falcon Dive Simulation — MATLAB/Simulink

A two-part simulation of a Peregrine Falcon during a high-speed dive, developed using MATLAB and Simulink.

## Project Overview

This project models the dynamics of a Peregrine Falcon during a dive, focusing on gravitational force, aerodynamic drag, velocity, and the change in aerodynamic conditions near the ground.

The simulation is divided into two parts:

### Part 1 — Dive Simulation

The first model represents the falcon during its dive and models the relationship between gravitational force, aerodynamic drag, acceleration, and velocity.

The model includes feedback of velocity into the aerodynamic drag calculation.

### Part 2 — Near-Surface Flight

The second model represents the later stage of the dive when the falcon is approximately 15 m above the ground.

At this stage, the aerodynamic conditions change as the wings are deployed, increasing drag and reducing the falcon's downward velocity.

## Tools Used

- MATLAB
- Simulink

## What I Practiced

- Building dynamic-system models in Simulink
- Translating physical equations into block diagrams
- Modeling gravitational and aerodynamic forces
- Using feedback loops
- Working with integrators and gain blocks
- Simulating velocity and acceleration
- Analyzing simulation results

## Repository Contents

| File | Description |
|---|---|
| `Peregrine_falcon_in_still_flight_model.slx` | Simulink model for the first part of the dive |
| `Peregrine_falcon_near_surface.slx` | Simulink model for the near-surface stage |

## Source & Attribution

This project is based on a simulation exercise from the **MathWorks Simulink Onramp** course and is shared as part of my learning and portfolio development.

The models are not presented as an entirely original simulation; this repository documents my implementation, exploration, and understanding of the course exercise.

## Certificate

I completed **100% of the Simulink Onramp** self-paced training course from MathWorks in September 2026.
## Simulation Results

### Part 1 — Dive Simulation

#### Simulink Model

![Part 1 Simulink Model](Simulink%20of%20Part%201.png)

#### Velocity Response

![Part 1 Velocity Response](Scope%20result%20for%201.png)

### Part 2 — Near-Surface Flight

#### Simulink Model

![Part 2 Simulink Model](Simulink%20of%20Part%202.png)

#### Simulation Results

![Part 2 Simulation Results](Scope%20Result%20for%202.png)
