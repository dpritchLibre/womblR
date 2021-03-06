# womblR
Implements a spatiotemporal boundary detection model with a dissimilarity metric for areal data with inference in a Bayesian setting using Markov chain Monte Carlo (MCMC). The response variable can be modeled as Gaussian (no nugget), probit or Tobit link and spatial correlation is introduced at each time point through a conditional autoregressive (CAR) prior. Temporal correlation is introduced through a hierarchical structure and can be specified as exponential or first-order autoregressive. Full details of the package can be found in the accompanying vignette.

See `vignette('womblR-example')` for usage.
