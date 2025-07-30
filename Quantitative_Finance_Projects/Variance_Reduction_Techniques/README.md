# Variance Reduction Techniques

In this project, I implemented and benchmarked various variance reduction techniques:
Antithetic Variates, Control Variates, Moment Matching, Stratified Sampling, Importance Sampling, and Sobol Sequences
achieving over 50% variance reduction in Monte Carlo pricing of a European call option.
While execution time was initially very short (due to the simplicity of the one-dimensional setting), performance differences between methods can be noisy and not always meaningful in practice. The techniques were applied to a single-asset European call option, depending on one stochastic factor. In higher-dimensional settings (e.g., basket options or path-dependent products), the relative benefit of certain variance reduction techniques may vary, and some methods may become less efficient or more complex to implement
