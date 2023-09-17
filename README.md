# R&D-exercise
## Overview
This exercise aims at optimising the power consumption of two machines by developing and comparing predictive models, judged by their accuracy metrics. The project involves two main steps:
* Machine Characterisation:
The exercise begins with the import of feather files containing data on two machines' inputs. The goal is to identify a model that accurately characterises the relationship between the machines' input parameters and power consumption. This characterisation is essential for achieving the project's second objective, which is optimisation.
* Optimisation:
The identified machine models from Step 1 are leveraged to determine the minimum power consumption with the optimal machine goods per hour (GPH) total of 9,000 GPH as a constraint. This optimisation process ensures that each machine operates at its minimum power consumption while meeting the production quota.


# The code is built with
The optimisation step is carried out using two Python libraries:
* Gurobi: The Gurobi optimisation library, under an academic license, is used to create and solve optimisation models efficiently. It plays a critical role in achieving the project's optimization objectives for the polynomial model output.
* Pulp Linear Programming: The Pulp library is employed for linear programming optimisation tasks, complementing the optimisation process and verifying the output of the testing linear model.
* Numpy, Pandas, and Scikit-Learn libraries


# Getting Started
To replicate and experiment with the project, follow these steps:
* Data Import: Start by importing the feather files containing the machine input data.
* Model Building: test different model fitting approaches including linear and polynomial regression, to characterise machine behavior.
* Optimisation: Use the identified machine models to perform optimisation tasks to achieve the desired machine goods per hour while minimizing power consumption.
* Dependencies: Ensure you have all the necessary dependencies, including the Gurobi optimization library, installed.
  
