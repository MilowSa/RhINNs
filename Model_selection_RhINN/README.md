# Model selection using RhINNs
This project is currently submitted to Rheologica Acta and is currently under review. The work is titled "Data-driven selection of constitutive models via Rheology-informed Neural Networks (RhINNs)."

This is a Pythonic implementation of a neural network platform that will select the best constitutive model for a given set of data. In this work, nine (9) constitutive models for describing the [quasi] steady-state shear stress of a material versus the imposed shear rate are added to this library, and the platform is tested for each set of data.

## Software/package requirements
In this project, the following packages are actively used:
1. tensorflow v2.7.0 (for the backbone),
2. numpy v1.22.1 (you know),
3. pandas v1.3.5 (pre-/post-processing), and
4. tensorflow_probability v0.7.0 (for L-BFGS optimization, optional). 
