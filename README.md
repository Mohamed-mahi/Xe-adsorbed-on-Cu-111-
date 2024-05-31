## About
Welcome to the repository for the implementation of a parameterized model developed by Righi and Ferrario. This model is designed to simulate the interaction potential between rare gases and a copper surface. The program has been rigorously tested and extended to include the construction of the Potential Energy Surface (PES) and the integration of the equation of motion using the Velocity Verlet algorithm. 

## Features
- Construction of the Potential Energy Surface (PES)
- Extension of the model using the Potential Function and Forces to integrate the equation of motion
- **Velocity Verlet Algorithm**: The integration of the equation of motion is performed using the Velocity Verlet algorithm, ensuring accurate trajectory simulations.
- Generation of trajectories from a common origin
- Calculation of the diffusion coefficient

## Methodology
The model parameters are derived on the basis of ab initio calculations, as described in the original paper by Righi and Ferrario.

## Usage
To use this code:
1. Clone the repository to your local machine.
2. Install the necessary dependencies.
3. Run the main script to perform simulations and calculate the diffusion coefficient.

## References
- Righi, M.C. and Ferrario, M. (2007). "Potential energy surface for rare gases adsorbed on cu (111): Parameterization of the gas/metal interaction potential." *Journal of Physics: Condensed Matter*, 19(30), p.305008. [Link to the paper](https://doi.org/10.1088/0953-8984/19/30/305008)

## Disclaimer
This code is provided as-is and without warranty. Use it at your own risk.

Feel free to contribute to this project by forking and submitting pull requests!
