# Leviathan: An Interactive Exploration
A Pedagogical Tool for Teaching Social Contract Theory

[Click Here to Play the Simulation](https://amall098.github.io/leviathan-interactive-simulation/)

## Overview
This project is an interactive, browser-based simulation of Thomas Hobbes' *Leviathan*. It was designed to bridge the gap between Political Philosophy and Computer Science students. It models the "State of Nature" as a system of variables, allowing students to experiment with parameters like "Mistrust," "Resource Distribution," and "Sovereign Power" to observe the algorithmic emergence of social stability or violence.

## Pedagogical Goals
* For Philosophy Students: To visualize the systemic fragility of the "State of Nature" and the logical necessity of the Sovereign.
* For Computer Science Students: To treat ethical theories as optimization problems, understanding how variable constraints influence macro-social outcomes.

## Technical Implementation
* Core Logic: JavaScript (ES6+) modeling state transitions based on Hobbesian game theory.
* Visualization: Chart.js for real-time data rendering of "Social Stability" vs. "Violence."
* Simulation Engine: A custom step-function (`runSimulationStep`) that calculates stability coefficients based on weighted role modifiers.

## Features
* Dynamic Role-Playing: Switch between Hobbesian, Lockean, and Rousseauian parameters.
* Moral Dilemma Engine: A specialized function (`presentDilemma`) that forces users to trade "Liberty" for "Security," simulating the foundational trade-off of the Social Contract.


