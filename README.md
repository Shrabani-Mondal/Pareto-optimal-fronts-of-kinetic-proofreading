# Pareto-optimal-fronts-of-kinetic-proofreading

DEhyd=-100, DEhyd=-50, DEhyd=-12.5 are the three-dimensional Pareto fronts we obtained for generalised Hopfield model for total hydrolysis energy 100, 50 and 12.5 respectively. 

symmetrized_fixed_energy  files are for the Symmetric choice of parameters.

The file hyperparameters.mat inside each folder can be loaded in MATLAB and it contains a struct with the values for the parameter that were held constant during the
simulation.

The optimization results are saved in the .mat formats. These are very good for maintaining a human-readable structure in the data, but they are pretty hard to work with. Moreover, MATLAB does not allow us to easily deal with the data visualization we have shown in the paper. To overcome this problem, the data plotting and post-processing are done by a different piece of code in R. We combine all the data produced from a single run in a .cvs file. Using the large .cvs file, we have generated the figures in R presented in the paper.
