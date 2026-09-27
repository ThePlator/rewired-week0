# Rewired Week 0

A small Python project exploring the leaky integrate-and-fire (LIF) neuron model in a Jupyter notebook.

## Overview

This repository contains a notebook-based simulation of a simple spiking neuron. The work focuses on the core ideas behind biological neuron dynamics:

- membrane voltage integration
- leak back toward resting potential
- threshold crossing and spike generation
- refractory period after a spike
- firing-rate behavior under different inputs

## Included files

- `01_lif_neuron.ipynb` — main notebook with the theory and simulations
- `pyproject.toml` — project configuration and dependencies

## Learning goals

The notebook walks through:

1. charging a neuron without spiking
2. simulating a LIF neuron with constant input
3. comparing simulated firing rates to theoretical expectations
4. exploring Poisson-driven spike generation

## Setup

Create and activate the environment, then install dependencies:

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

If you are using the project metadata file instead, you can also install with:

```bash
pip install .
```

## Run the notebook

Open the notebook in Jupyter and run the cells in order:

```bash
jupyter notebook 01_lif_neuron.ipynb
```

## Dependencies

The project uses:

- NumPy
- Matplotlib
- Jupyter / IPython

## Notes

This is a beginner-friendly computational neuroscience exercise intended to connect the LIF equation to an actual simulation and visual output.
