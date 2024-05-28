# Automated DCGs - Capstone Project 2024
This project focuses on implementing and verifying aDCGs for noise resilient ST-0 qubit operations. The project uses a Jupyter notebook created in VS Code, leveraging Julia packages like QuantumOptics, LinearAlgebra, Optimization, and Plots to perform and visualize quantum calculations and optimisations.
## Jupyter Notebook
The core of this project is a Jupyter notebook, created and managed through Visual Studio Code, that orchestrates and performs quantum calculations. The notebook leverages a suite of powerful Julia packages to facilitate the simulations, optimizations, and analyses necessary for the development of aDCGs.
## Julia Packages Utilised
QuantumOptics: This package provides the tools required to simulate quantum optical systems, enabling the modeling of the qubit states and their interactions within the quantum system.

**LinearAlgebra:** Essential for performing various linear algebra computations, which are fundamental to quantum state manipulations and transformations.

**OptimizationOptimJL:** A robust optimization package used to fine-tune the control parameters and optimize the quantum gate implementations.

**Optimization:** Used in conjunction with OptimizationOptimJL, this package aids in solving the complex optimization problems associated with quantum control.

**Random:** Provides the capability to generate random numbers and distributions, necessary for stochastic simulations and error analyses.

**Statistics:** Facilitates the statistical analysis of the simulation results, ensuring the accuracy and reliability of the quantum operations.

**ColorSchemes:** Enhances the visualization of data with predefined color schemes, making it easier to interpret the results.

**Plots:** A powerful plotting library used to create detailed visual representations of the simulation data, aiding in the analysis and presentation of results.
### Key-Features
**Simulation of Quantum Systems:** Utilize QuantumOptics to model the behavior of qubits and their interactions, providing a realistic representation of the quantum system.

**Error Analysis and Correction:** Implement advanced error correction strategies using optimized control pulses, with a focus on minimizing the effects of environmental noise and operational errors.

**Optimization of Control Parameters:** Apply multi-objective optimization techniques to fine-tune the parameters, ensuring high-fidelity quantum gate operations.

**Visualization and Analysis:** Generate comprehensive plots and statistical analyses to visualize the performance and robustness of the aDCGs under various conditions.
## How to View
1. **Online Viewer:** Navigate to the GitHub repository, go to the 'src' folder, click on the notebook file ('Automated DCGs - Capstone project 2024.ipynb'). Here, GitHub provides a built-in viewer for Jupyter Notebooks.
## How to Use
1. **Clone the Repository:** Download the repository to your local machine using 'git clone'.
   
2. **Install Dependencies:** Ensure you have Julia installed then, in the Julia REPL, ensure all necessary Julia packages are installed.
   
3. **Run the Notebook:** Open the Jupyter notebook in Visual Studio Code and execute the cells to perform the quantum calculations and analyses.
