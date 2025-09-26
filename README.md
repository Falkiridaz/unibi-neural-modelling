# Neuronal Network Model

A Python implementation of a somewhat biologically realistic neuronal network based on multi-compartment modeling.

## Overview

This repository contains a computational model of neuronal networks that builds upon:

- **Hodgkin-Huxley Model**: The classic model of action potential generation in neurons
- **Cable Theory**: Mathematical framework for electrical signal propagation in neuronal processes
- **Multi-Compartment Models**: Division of neurons into discrete segments with distinct electrical properties

## What's Included

- Multi-compartment neuron implementation with soma, axon, and dendrites
- Hodgkin-Huxley dynamics with ion channels (Na⁺, K⁺, Ca²⁺, etc.)
- Synaptic connections between neurons
- Network simulation
- Rudimentary visualization for analysis

## Quick Start

```bash
pip install numpy matplotlib seaborn networkx
cd src/
python demo.py
```

## Structure

- `src/` - Main implementation
  - `neuron.py` - Multi-compartment neuron class
  - `compartment.py` - Individual compartment with Hodgkin-Huxley dynamics
  - `network.py` - Network of connected neurons
  - `parameters.py` - Model parameters and config
  - `demo.py` - Example simulation and visualization

## Requirements

- Python 3.7+
- NumPy
- Matplotlib
- Seaborn
- NetworkX
