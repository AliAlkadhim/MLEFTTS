# IDEAS

## A couple of ideas

1. There should be better comparison and estimation of the confidence intervals and proving that it has the right coverage
2. The PDF uncertainties should be constrained from the spin observables - eg see https://www.youtube.com/watch?v=HhdiIQf0NRg&t=1149s&ab_channel=HEPSoftwareFoundation
3. The background estimation should be done more rigorously, eg like in the CMS paper in choosing a control region and background-subtracting or ML tools (lots of ideas there)
4. The computation time is clearly something that needs to be improved in madminer: the overhead of madgraph might not be able to be improved, but the ML/inference parts can. The code should be able to use lots of parallelization with eg numba
5. Using real data (MiniAODs), which is an absolute necessity - but using it in an efficient and fast manner (Miniaod -> NanoAOD -> numpy as opposed to hdf5)
6. A better understanding of the top spin correlation observables (from my part)
