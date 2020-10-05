# AtomicGraphNets.jl
![Run tests](https://github.com/aced-differentiate/AtomicGraphNets.jl/workflows/Run%20tests/badge.svg)
[![codecov](https://codecov.io/gh/aced-differentiate/AtomicGraphNets.jl/branch/master/graph/badge.svg)](https://codecov.io/gh/aced-differentiate/AtomicGraphNets.jl)

Herein you can find the beginnings of a package to implement [Crystal Graph Convolutional Neural Nets](https://arxiv.org/abs/1710.10324) in Julia. It makes use of the [Flux](https://fluxml.ai) ecosystem for model building and the [JuliaGraphs](https://github.com/JuliaGraphs) ecosystem for graph representation and visualization, as well as adapting some features from [GeometricFlux](https://github.com/yuehhua/GeometricFlux.jl).


## Getting Started

1. Clone this package to wherever you want to play.

2. Go and try out the example in examples/example1/ – it has its own README file with detailed instructions.

## Note about Conda.jl
This package depends on ChemistryFeaturization.jl, which depends on some pretty hefty Python packages that in turn have many of their own dependencies. If you have an existing Conda.jl installation, you may be able to install everything without issue, but the cleanest approach will likely be to create a conda environment just for this package and install the dependencies from scratch there.

## Future plans
* make tests, docs
* fix random weird stuff as noted in comments
* more options for features, layers, network architectures...

## Contact
Please feel free to fork and play, and reach out here on GitHub or to rkurchin [at] cmu [dot] edu with suggestions, etc.!
