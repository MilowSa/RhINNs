# Model selection using RhINNs
This project is currently submitted to Rheologica Acta and is currently under review. The work is titled "Data-driven selection of constitutive models via Rheology-informed Neural Networks (RhINNs)."

This is a Pythonic implementation of a neural network platform that will select the best constitutive model for a given set of data. In this work, nine (9) constitutive models for describing the [quasi] steady-state shear stress of a material versus the imposed shear rate are added to this library, and the platform is tested for each set of data.

## Software/package requirements
In this project, the following packages are actively used:
1. python v3.9.12, 
2. tensorflow v2.7.0 (for the backbone),
3. numpy v1.22.1 (you know),
4. pandas v1.3.5 (for pre-/post-processing),
5. tensorflow_probability v0.7.0 (for L-BFGS optimization, optional),
6. pymc3 v3.11.5 (for Bayesian Inference Criterion (BIC) benchmark, optional), and
7.  scipy v1.7.3 (for Trust Region Reflective benchmark, optional).

## Hardware/OS tested
The program (excluding tensorflow_probability) was tested on a MBP M1 Max (64 GB RAM) running macOS Monterey v12.3.1. The program, excluding tensorflow_probability was also briefly tested on a Dell OptiPlex 7440 AIO (Core i7-6700 CPU @ 3.40 GHz, 16 GB RAM) running Windows 10 Enterprise 21H1. The  versions listed above are all for the MBP machine.


