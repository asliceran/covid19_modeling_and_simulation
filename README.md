# Modeling COVID-19 Transmission in Turkey Using the SIR Model

A computational simulation of COVID-19 transmission in Turkey using the SIR epidemiological model, Euler's method, and time-dependent transmission rates to examine how policy changes and tourism mobility influenced disease dynamics.

---

## Project Overview

This project was completed as part of a computational modeling assignment at Minerva University.

The objective was to model the spread of COVID-19 in Turkey between **April 1, 2020** and **December 31, 2020** using the classical SIR (Susceptible–Infected–Recovered) model. To better capture real-world conditions, I extended the standard model by introducing a piecewise transmission rate that changes in response to major policy interventions, including the June 1st normalization and increased tourism mobility.

---

## Research Question

How do changes in government policies and population mobility influence the spread of COVID-19, and can a modified SIR model capture these changes over time?

---

## Methodology

The project models disease transmission using the SIR system of differential equations.

To numerically solve the model, I implemented **Euler's Method** in Python. Rather than assuming a constant transmission rate, the simulation dynamically updates the transmission parameter according to predefined policy change dates, allowing the model to better reflect real-world conditions.

The implementation also verifies that the total population remains constant throughout the simulation, ensuring the correctness of the numerical solution.

---

## Visualization

The simulation generates a multi-series line graph illustrating the evolution of:

* Susceptible population (S)
* Infected population (I)
* Recovered population (R)

Vertical reference lines indicate major government policy changes, making it easier to interpret how changes in transmission rates affect the trajectory of the pandemic.

<img width="993" height="633" alt="3Untitled" src="https://github.com/user-attachments/assets/d876d04a-0b73-431d-8b2a-c04ac5aeb937" />

---

## Key Findings

The model demonstrates how modifying transmission rates over time significantly changes infection dynamics compared to a standard SIR model with fixed parameters.

By incorporating policy interventions into the simulation, the model provides a more realistic representation of epidemic behavior while illustrating how mathematical assumptions influence computational predictions.

---

## Technologies Used

* Python
* NumPy
* Matplotlib

---

## Skills Demonstrated

* Mathematical modeling
* Epidemiological simulation
* Differential equations
* Euler's Method
* Computational modeling
* Scientific programming
* Data visualization
* Algorithm design
