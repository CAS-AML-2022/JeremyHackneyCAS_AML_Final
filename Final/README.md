# Repository of notebooks, data, output and paper for the final project of CAS AML 2022-23 University of Bern

# Paper:
  report on method, tests, data, model results, discussion
# Corrections:
  added 18.06.2023 to correct errors in the text
# Data:
  UTD2019 is a set of traffic counts, used with permission from ETHZ (IVT). Do not distribute.
# Output:
  Model weights, output values, plots and tables from the models.
  NOTE: the MCMC trace (.npy format) is > 100MB and too large to store, here. Please let me know if it is needed
# Notebooks:
  1. CompressedSensing07 demonstrates toy Model 1 from Dey at al. with CVXPY and Method of Moments
  2. CompressedSensing08 demonstrates toy Model 1 from Hazelton with CVXPY and Method of Moments
  3. MCMC_Poisson_03 demonstrates MCMC on toy Model 1 from Dey et al. compared with CVXPY
  4. DNN_2 demonstrates toy Model 1 from Dey et al. with MLP and CVXPY
  5. Download_OSM demonstrates downloading and saving a map from Open Street Maps
  6. MCMC_Poisson_04 demonstrates reading and preparing OSM graph and UTD19 counts,
    data cleaning and preparation,
    solution with CVXPY, MCMC, MLP
  7. AE_03 demonstrates the experimental set of Autoencoders and MLP's
  8. Analysis2 reads output of individual models to create analysis plots if any were in error or forgotten in the original runs
  9. Analysis3 compares output across models
