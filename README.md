# mvgpr_as
Code for the paper on surrogate modeling of atomistic simulation computations of basic structural alloy properties.

This repository contains a zip file with the corresponding RStudio project.

The project contains the following:

1. An R script mvgpr_functions with the necesary functions for fitting the models and plotting the results.
2. Raw data in the as_data.xlsx file. The columns are:
     a. Name: alloy or pure metal name
     b. Type: pure or alloy
     c. n_elements: number of elements in the alloy
     d. Primary and Secondary metals
     e. Columns with basic property predictions from ASs
     f. Elemental percentage from each element in the alloy
     h. Train: 1 if point must be in the training set and 0 otherwise
4. mvgpr_as_paper_results.Rmd file to run the experiments presented in the paper.
5. binary_viz folder with the app.R file used to run a Shiny dashboard of the predictions for binary alloys.

The code must be executed in RStudio by first oppening the MVGPR_AS.Rproj file. Otherwise, RStudio may not find all data files and scripts.
