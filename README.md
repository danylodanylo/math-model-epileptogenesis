# math-model-epileptogenesis

All materials contained in this repository are complementary to the manuscript "Phenomenological model of neuroimmune interactions in epileptogenesis" written by Danylo Batulin, Fereshteh Lagzi, Annamaria Vezzani, Peter Jedlicka and Jochen Triesch.

All scripts are written as Jupyter notebooks in Python version 3.7.4.

Figures production scripts (“FigureProduction_N”) are consistent with the numbering of the figures in the manuscript. Data is not uploaded to GitHub and can be generated directly (by running scripts in “DataGenerationScripts” folder). Alternatively, running figure production scripts will create corresponding data folders and execute the data generation scripts before figure generation. Figures will be saved in the corresponding folder “Figures/FigN”. After being generated, data will not be re-generated in case the figure production script is executed again.

DataGenerationScripts folder also contains auxiliary scripts that will be used by “FigureProduction_N” scripts.

Parameters of the model can be found in “DataGenerationScripts/load_default_parameters.ipynb” and Appendix 4.

Simulation-specific parameters can be found in data generation scripts and summarized in Appendix 5.

Data from animal model studies can be found in “DataGenerationScripts/load_animal_model_data.ipynb” and summarized in Appendix 6. 

Scripts used in the analysis of the dynamical system (Appendix 3; Appendix 7) can be found in the “AnalysisScipts” folder.
