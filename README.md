# Data_Science_Research

Research on the effects of adding Noise (Gaussian & Laplace) to a dataset. Error calculations to analyze effects. The goal is to preserve patterns in the dataset while maintaining privacy of individuals in the dataset.

In main.py:

gaussian_mech() adds gaussian noise to the dataset

laplace_mech() adds laplace noise to the dataset

workloads() generates 200 queries ranging in size from 1 to 3

gaussian_error_calc() calculates the error for different epsilon values for the dataset after adding gaussian noise

laplace_error_calc() calculates the error for different epsilon values for the dataset after adding laplace noise

Matplotlib is used to generate the graphs to show how the error changes for different values of epsilon

Epsilon decides the amount of privacy
