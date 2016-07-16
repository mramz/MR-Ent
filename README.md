# MREnt
MaxEnt Matrix Factorization

Based on the Netflix prize this uses bayesian matrix factorization and maximum relative entropy (ME) to prediction movie rating. ME is used to put contraints based on movie genres on the movie latent features. Hierarchical bayesian matrix factorization for the user latent features as found in (Salakhutdinov Mnih 2008) at https://www.cs.toronto.edu/~amnih/papers/bpmf.pdf.

I used the movie lens data set (http://grouplens.org/datasets/movielens/) which includes information about the movies include the genre.

The prior user and movie latent features where obtained by using stochastic gradient descent.

Future releases are to create a mathematica package that includes stochastic gradient descent for the prior information.


TO RUN

Change the path in the notebook for the priors, data, and side information include in the importData folder. Then evalute the notebook. THe number of iteration can be change in the RUN section of the notebook in the 4th varible.


Copyright 2016, Mick Ramsey, All rights reserved

