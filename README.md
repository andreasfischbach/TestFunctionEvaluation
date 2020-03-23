# TestFunctionEvaluation
This repository delivers supplementary material for the article Improving the Reliability of Test Functions Generators.

## Jupyter Notebook
In mixedModels.ipynb you find the code to evaluate the performance of optimization algorithms based on an ANOVA approach w.r.t not only fixed factors, but also factors from a random distribution.

## Data frames
The performed case studies covered two scenarios:
- (S)ingle (A)lgorithm on (M)ultiple (P)roblem instances (SAMP)
- (M)ultiple (A)lgorithms on (M)ultiple (P)roblem instances (MAMP)

The SAMP results can be found in data/2018-05-29.GLG.tuned.GenSA.samp.RData.
Generalized Simulated Annealing (GenSA) was used on 4 randomly created gaussian landscape instance, 30 repetitions were performed on each instance.

The MAMP results can be found in data/2019-03-21.GLG.tuned.SPOT.GenSA.DEoptim.RS.mamp.RData.
Generalized Simulated Annealing (GenSA), Sequential Parameter Optimization Toolbox (SPOT), Differential Evolution (DEoptim) and a simple Random Search (RS) were used on 4 randomly created gaussian landscape instance, 30 repetitions were performed on each instance.
