# UK GP visits data
Bayesian modeling for GP visits using partial and complete pooling. Analyzes demographic and regional factors. Utilizes PyMC3 for modeling and visualization. Prior and posterior predictive checks included.

This project implements Bayesian modeling techniques to analyze and predict General Practitioner (GP) visits based on demographic and regional factors. The project includes two main modeling approaches: partial pooling and complete pooling using the Zero-Inflated Poisson function as its likelihood function. 

The partial pooling model incorporates hierarchical Bayesian modeling to account for both group-level and individual-level variations in GP visit counts across different demographic clusters and regions. On the other hand, the complete pooling model assumes homogeneity across all groups and estimates a single set of parameters for the entire dataset.

The project utilizes the PyMC3 library for Bayesian modeling and provides visualizations of the model structures and posterior distributions. It also includes prior predictive checks and posterior predictive checks to assess each model's performance and predictive accuracy.
