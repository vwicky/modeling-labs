# here's stored all the source code to my Modeling labs

## Labs Overview

### Lab 1
- **Objective**: *Black-box model concept and establishing the relationship between its input and output parameters*
- **Tools Used**: *Python*

### Lab 2
- **Objective**: *Modeling of dynamic systems.*
- **Tools Used**: *Python*
- **Summary**: 
  1. Description of building an ecological system model (Predator–Prey).
  2. Description of building a model for epidemic spread.
  3. Time-dependence plots of key parameters in the studied dynamic systems.
  
### Lab 3
- **Objective**: *Modeling of spatially distributed processes*
- **Tools Used**: *Python*
- **Summary**: 
  1. Description of building a heat conduction model.
  2. 3D plots of the numerical and analytical solutions to the heat conduction problem, along with the computed numerical error values between them.

### Lab 4
- **Objective**: *Simulation of dynamics and investigation of Petri net properties.*
- **Tools Used**: *Python*, *PetriUkr*
- **Summary**: 
  1. Use the PetriNet software tool to simulate the dynamics of a Petri net according to the assigned variant.
  2. Construct the reachability graph of the Petri net and analyze its dynamics to determine key properties: boundedness, safeness, conservativeness liveness, and reachability.
  3. Summarize the main conclusions based on the obtained results.

### Lab 5
- **Objective**: *Modeling of queueing systems using the GPSS environment.*
- **Tools Used**: *GPSS*

### Lab 6
- **Objective**: *Construction of a Bayesian network based on a real dataset*
- **Tools Used**: *Python*
- **Summary**: 
  1. Data preparation: Load or create a dataset with categorical variables (from 5 to 10 attributes). Perform necessary preprocessing: handling missing values, discretizing numerical variables, and re-coding.
  2. Network structure determination: Build a network structure graph that defines the relationships between variables (using `BayesianModel([...])); justify the choice of directions between nodes (based on domain knowledge or assumptions).
  3. Parametric learning: Train the model parameters using the dataset with BayesianEstimator or MaximumLikelihoodEstimator.
  4. Inference execution: Implement the computation of conditional probability for the target variable given the specified evidence, using VariableElimination or BeliefPropagation."

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/vwicky/modeling-labs.git

## Technologies Used
1. Python: sklearn, pgmpy, matplotlib, networkx, plotly
2. PetriUkr
3. GPSS World Student Version