# Time-Dependent Model of Female Mosquito Swarm Dynamics

This repository contains a Python implementation of a time-dependent model simulating the changing composition of female *Anopheles* mosquitoes within swarms. It estimates the proportions of virgin, mated, and total effective females over time, under biologically informed assumptions about mating success, swarm residence time, and swarm depletion dynamics.

## Overview

The model is built to support the analysis presented in the PhD thesis *Behavioral Ecology and Spatial Dynamics of Anopheles coluzzii Swarms*, particularly in relation to female swarm participation and mating dynamics.

Key outputs include:
- Time series of virgin, mated, and total effective females.
- Sensitivity analyses for mating latency (`tau`) and initial mating status ratio (`r`).
- Confidence interval representation for parameter uncertainty.

## Features

- Simulation of swarm dynamics using exponential decay models.
- Incorporation of experimental variation in swarm residence time.
- Sensitivity analysis across biological parameters.
- Publication-quality plots using Matplotlib.

## Requirements

- Python 3.7+
- `numpy`
- `pandas`
- `matplotlib`
