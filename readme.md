# Quantum USB Research - Exploring High Energy States

Authors:
- Adam Blazejczak
- Burak Kucuktopal

Promotor:
- Miloš Nesladek

Supervisors:
- Darya Meniailava
- Michael Petrov

## Abstract

NV point defects in diamonds have been studied extensively in literature, initially using low laser powers and the four-level model. However, recent investigations by Ádám Gali through ab initio calculations in higher power regimes introduced a fifth level [Gali], to consider state switching between the $NV^{-}$ and $NV^{0}$.
The theoretical model initially predicted zero photoluminescence (PL) at high laser powers, but ongoing experiments have indicated a possible high energy $n_{8}$-state, close to the conduction band, which would lead to non-zero asymptotic PL at high laser power. To shed light on this discrepancy, our research group modeled a NV-center with a six-level state, and derived a subsequent formula to calculate the population of the excited state at higher laser powers. Saturation curve measurements are obtained to study the validity and presence of this new high energy state. Setup refinements are required before making conclusions about the existence of state $n_{8}$.

During measurements, PL changes were observed due to changes in applied voltage on the sample. Investigation into PL dependence on potential has been investigated extensively using Optically Detected Magnetic Resonance (ODMR) and Rabi Oscillation, which confirmed initialization issues when cycling potential from non-zero to zero voltages, which is something researchers should be taking into account going into future research.


## Repo content

This repository contains the majority of measurted data, and its post-processing in Python.

## Required libraries
run the pollowing, after installing python 3.7

```
pip install pandas numpy matplotlib seaborn jupyter notebook scipy scikit-learn
```

