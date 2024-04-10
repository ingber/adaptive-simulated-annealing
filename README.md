ADAPTIVE SIMULATED ANNEALING (ASA)


Lester Ingber
<ingber@caa.caltech.edu>


Adaptive Simulated Annealing (ASA) is a C-language code developed to statistically find the best
global fit of a nonlinear constrained non-convex cost-function over a D-dimensional space. This
algorithm permits an annealing schedule for “temperature” T decreasing exponentially in annealing-time
k, T = T0 exp(−ck^(1/D)). The introduction of re-annealing also permits adaptation to changing sensitivities
in the multi-dimensional parameter-space. This annealing schedule is faster than fast Cauchyannealing,
where T = T0/k, and much faster than Boltzmann annealing, where T = T0/ln k. ASA has over 100
OPTIONS to provide robust tuning over many classes of nonlinear stochastic systems.
