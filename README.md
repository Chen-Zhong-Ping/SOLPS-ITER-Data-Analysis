# SOLPS-ITER-Data-Analysis
shell scripts and IPython notebooks doing data analysis for SOLPS-ITER simulations
## Purpose
These scripts provide a routine for doing data analysis for SOLPS-ITER simulations. Although they focus on the specific data sets that are most relevant to advanced divertor research, the methods are applicable to all the data produced in a SOLPS-ITER run.
## Parts
There are two parts.
1. Shell scripts
Located in the folder "Chen's b2plot scripts for SOLPS-ITER". These shell scripts execute a set of *b2plot* commands that produce formatted text files containing structured data.
To use them, call/execute the master script "Chen_b2plotSOLPSITER_master" in any SOLPS-ITER run directory. The output data will be stored in the created "analysis-data-for-plot" directory.
2. IPython notebooks
Located in the folder "IPythonNotebooksForDataVisualization". These IPython notebooks read the data files produced by the above shell scripts and perform analyses including calculation and plotting. Located in the 4 folders are,
  - IPythonNotebooks: A set of example notebooks demonstrating how to do various analyses.
  - Data: A set of real simulation data serving as examples for the notebooks.
  - packages: A few custom classes to handle the formatted SOLPS-ITER data files.
  - Colors: A few examples for custom color codes that are used in producing 2D patch plots.
