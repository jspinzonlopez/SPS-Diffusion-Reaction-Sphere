# Reaction–Diffusion Model

Python code used for the numerical solution of the reaction–diffusion model presented in the associated manuscript.

The model describes the diffusion and second-order reaction of a liquid-phase reactant within spherical porous particles containing a solid-phase reactant.

## Requirements

- Python 3
- NumPy
- SciPy

Install dependencies with:

    pip install numpy scipy

## Usage

Run the function:

    second_order_screening(k)

where `k` is the second-order reaction rate constant.

The code calculates the concentration profiles, the time required to reach 99% conversion, the normalized reaction time, and the reaction–diffusion parameter.

## Reproducibility

The code was used for the numerical simulations and sensitivity analysis reported in the associated publication.

## Citation

Please cite the associated publication when using this code.
