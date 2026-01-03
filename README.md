# Reaction Wheel Attitude Control (MATLAB)

## Overview
This project simulates satellite attitude regulation using a single
reaction wheel and PD control. Parameters are loosely inspired by
Hubble-class spacecraft.

## Model Scope
This simulation models **single-axis (1-D) attitude dynamics** of a rigid
satellite with one reaction wheel. The model captures rotational dynamics,
PD control, torque saturation, and angular momentum exchange along a single
principal axis.

Extension to full 3-D rigid-body dynamics is planned.

## Features
- PD attitude control law
- Reaction wheel dynamics
- Torque saturation
- Angular momentum conservation verification
- Time-history plots of attitude, rates, and torque

## Governing Equations
- Satellite:  I_s * ω̇ = T_w + T_d
- Wheel:      I_w * ω̇_w = -T_w

## How to Run
1. Open MATLAB
2. Run `reaction_wheel_attitude_control.m`
3. Enter initial wheel speed and attitudes when prompted

## Example Output
- Satellite angular velocity vs time
- Wheel angular velocity vs time
- Attitude convergence
- Total angular momentum conservation

## Author
Bilal Ahmad 

Aerospace Engineering Student
