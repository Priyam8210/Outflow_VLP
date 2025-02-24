# Tubing Intake and Performance Curve Simulation

## Overview
- The Python script for single_phase_flow simulates the tubing intake for gas wells. The calculations involve pressure losses due to gravity, friction, and acceleration as gas flows through a wellbore.

- The Python script for multiphase_tic simulates the tubing intake curves for multiphase flow profile. The calculations involve pressure losses due to gravity, friction, and acceleration as gas flows through a wellbore.

## libraries used
- math
- NumPy
- Matplotlib

## Features
- Uses standard fluid properties correlation for oil and gas properties calcuation.
- Uses Newton-Raphson method to solve nonlinear equations to find gas compressiblity factor.
- Implements Hagedorn and Brown correlation for multphase flow for find holdup values.
- - Determines gas density or mixture density, gas or mixture viscosity, and pressure losses.
- Plots Tubing Intake Curve and Tubing Performance Curve.

## Inputs
- Tubing diameter
- Pipe roughness
- Standard gas flow rate
- Total well depth
- Temperature and pressure profile
- Inclination angle of wellbore
- Some fluid properties for oil, gas and water.

## Calculation Methodology
1. Iterates over different gas flow rates.
2. Computes different fluid properties for oil, gas and water.
3. Computes gas compressibility factor using some corellation with implementation of newton raphson method.
4. Computes holdup using Hagedorn and Brown correlation.
5. Computes different mixture properties.
6. Computes pressure drop due to head loss, friction loss, and acceleration loss.
7. Calculates pressure losses and updates pressure profile.
8. Plots the tubing intake curve.
