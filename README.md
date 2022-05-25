# Predicting pedestrian injuries within the youth population in the state of New York

This project aims to investigates the number of pedestrian injuries in the youth population in the state New York in the time period 2005-2014.
The pedestrian injuries have been modelled through various bayesian spatial count models with and without the inclusion of non-linear modelling.

The exploratory notebook contains a thorough descriptive analysis of the data that shows insights into the different distributions. Moreover a mapping has been made in order to see how the pedestrian injuries distributes over the state of New York. 

The modelling notebook implements different Bayesian Spatial model. 

All models have been made using the module pyro in python, thus it is a requirement to have pyro installed. 

Following models have been develop:
* Linear regression 
* Linear regression with feature selection
* Bayesian poisson regression
* Bayesian NB regression
* Neural network with bayesian poisson regression
* Neural network with NB bayesian regression
* Hierarchical model with poisson
* Hierarchical model with NB 
* Hierachical model with poisson and NN component
* Hierachical model with NB and NN component



