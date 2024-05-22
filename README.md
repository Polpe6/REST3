# REST3
This repository will provide the necessary files to undergo a REST3 simulation and a description on how to do it. There are 2 main parts, the preprocessing part will show how to organize all the necessary files in the specific directories as well as editing and processing the topologies with its adapted parameters for Solute Tampering before the simulation actually starts. The simulation part is the one that will take preprocessed files and directories and will actually run the Replica Exchange Dynamics for the specified parameters.

## Preprocessing
In order to prepare the directory where you will be executing the slurm files you will need to undergo a preprocessing phase. For that you will need the following files from this repository: `partial_tempering.sh`, `gennewtop.sh`, `GlobalScript.py`, `rest.mdp` (at the preprocessing phase you just need a file called rest.mdp but it could be empty for all is needed), and `run_python_ft3.slurm`.

