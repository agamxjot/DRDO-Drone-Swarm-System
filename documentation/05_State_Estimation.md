# Probabilistic State Estimation

## 1. Introduction

The project includes a particle-filter-based experiment for representing uncertain spatial states in a simulated environment.

The implementation maintains a collection of candidate state hypotheses and updates their statistical weights using simulated observations.

## 2. Particle Representation

A particle represents one possible state hypothesis.

The implementation initializes a collection of particles around an initial spatial estimate.

Each particle maintains a numerical coordinate representation.

## 3. Estimation Workflow

The experiment includes the following general stages:

1. Particle initialization.
2. State prediction.
3. Observation-based weight updating.
4. Particle resampling.
5. Estimate calculation.
6. Visualization of the particle distribution.

## 4. Uncertainty Representation

The particle distribution provides a visual representation of uncertainty in the estimated state.

The weighted distribution is used to calculate an aggregate estimate.

## 5. Visualization

The software provides visual representations of particle distributions and estimated positions in a simulated coordinate space.

## 6. Limitations

The available experiments use simulated trajectories and observations. Their outputs should not be treated as validated performance measurements from physical sensors.