# Ising-Model
## Project written in Python that simulates the Ising model for arbitrary size of lattice and shows the final spin arrangement and graph the Magnetization, Energy, Heat Capacity and Magnetic Susceptibility vs. Temperature.

This project is written in Python and uses the Ising model to simulate the behavior of a system of magnetic particles on a lattice. The Ising model is a mathematical model of ferromagnetism in statistical mechanics, where each particle (or spin) can be in one of two states (+1 or -1). The spins interact with their nearest neighbors and an external magnetic field, and the energy of the system depends on the spin configuration. The project allows the user to specify the size of the lattice, the strength of the interaction, and the external field. The project then shows the final spin arrangement and plots the following physical quantities as functions of temperature: 

- Magnetization: the average spin per particle, which measures the net magnetic moment of the system.
- Energy: the total energy of the system, which depends on the spin configuration and the external field.
- Heat Capacity: the rate of change of energy with respect to temperature, which measures how much energy is required to increase the temperature of the system.
- Magnetic Susceptibility: the rate of change of magnetization with respect to the external field, which measures how responsive the system is to an applied magnetic field.

The project uses a Monte Carlo method to generate random spin configurations and calculate the physical quantities. The Monte Carlo method is a numerical technique that relies on repeated random sampling to obtain approximate solutions. The project uses the Metropolis algorithm, which is a specific type of Monte Carlo method that generates spin configurations according to the Boltzmann distribution. The Boltzmann distribution is a probability distribution that describes the likelihood of a system being in a certain state at a given temperature. The Metropolis algorithm ensures that the system reaches thermal equilibrium, where the physical quantities are independent of the initial spin configuration.

