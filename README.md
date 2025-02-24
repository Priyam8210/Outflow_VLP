# Tubing Intake and Performance Curve Simulation

## Overview
-The Python script for single_phase_flow simulates the tubing intake for gas wells. The calculations involve pressure losses due to gravity, friction, and acceleration as gas flows through a wellbore.

-The Python script for multiphase_tpr simulates the tubing intake curves for gas wells. The calculations involve pressure losses due to gravity, friction, and acceleration as gas flows through a wellbore.

## libraries used
- math
- NumPy
- Matplotlib

## Features
- Computes tubing intake curve and tubing performance curves for single phase gas flow and also for multiphase flow.
- Uses Newton-Raphson method to solve nonlinear equations to find gas compressiblity factor.
- Determines gas density or mixture density, gas or mixture viscosity, and pressure losses.
- Plots Tubing Intake Curve and Tubing Performance Curve.

## Inputs
- Tubing diameter
- Pipe roughness
- Wellhead pressure
- Bottomhole pressure
- Standard gas flow rate
- Flowing bottom-hole temperature
- Flowing top-hole temperature
- Total well depth
- Inclination angle of wellbore

## Calculation Methodology
1. Iterates over different gas flow rates.
2. Computes gas density,gas viscosity,  and velocity.
3. 
4. Computes pressure drop due to head loss, friction loss, and acceleration loss.
5. Calculates pressure losses and updates pressure profile.
6. Plots the tubing intake curve.
