# DataDrivenDiffEq.jl

DataDrivenDiffEq.jl is a package for estimating equation-free and equation-based models for discrete and continuous differential equations.

Opposed to parameter identification, these methods aim to find the governing equations of motion automatically from a given set of data. They do not require giving as input a known model. Instead, these methods take in data and return the differential equation model which generated the data.

There are various different avenues in which structural estimation can occur. However, the main branches are: do you want to know the equations in a human understandable manner, or is it sufficient to have a function that predicts the derivative and generates correct timeseries? We will refer to methods which return symbolic forms of the differential equation as structural identification, while those which return functions only for prediction as structural estimation.

## Package Overview

DataDrivenDiffEq currently implements the following algorithms for
structural estimation

+ Dynamic Mode Decomposition
+ Extended Dynamic Mode Decomposition
+ Sparse Identification of Nonlinear Dynamics
+ Implicit Sparse Identification of Nonlinear Dynamics


## Installation

To use 'DataDrivenDiffEq.jl' simply install it via:

```julia
]add DataDrivenDiffEq
using DataDrivenDiffEq
```
