# Computational Neuroscience Tutorial 2021

Introduction on Spiking Neural Networks (SNNs) by using PyNN on the SpiNNaker neuromorphic system.

## Instruction to use the material:

1. make the EBRAINS credentials to access the SpiNNaker server with this link https://spinn-20.cs.man.ac.uk/hub/login
1. login on the Jupyter Lab interface
1. clone the repository `<git clone https://github.com/albertoarturovergani/CNS-tutorial-2021>`
1. Open the directory `SpiNNaker/` and run the [CNS tutorial notebook](CNS_tutorial.ipynb)

## Content:

### SNNs design 
1. neurons
    - cell types
    - populations
    - recording variables
1. connections
    - synapse types
    - connections types
    - projections

### network examples
- [1D small network](eg_1D_small-network.ipynb)
- [1D decaying network](eg_1D_decaying-network.ipynb)
- [1D persistent network](eg_1D_persistent-network.ipynb)
- [1D diverging network](eg_1D_diverging-network.ipynb)

### topics for an advanced class (aka, what there's not in this tutorial)
- bio-realistic neural network 
- large scale computation
- model replicaton (i.e., reproduce results from paper)
- parameters explorations

### knowledge assumptions: 

- basis of spiking neural network theory
- familiarity with physical quatities related to electric circuits (e.g., voltages, conductances, currents, capacitances, etc)
- basic python coding (numpy, work with dictionaries, some matplotlib tools, etc)

### expected take-home-points: 
- import the simulator
- setup the simulator
- decide the cell types 
- design the populations
- define the synapse types
- select the connection algorithm
- make the projections 
- idealize the stimulus
- run the simulation
- save the results
- close the simulations
- recover the result
- postprocessing (visualization, statistics, etc)

## Links
- [PyNN](http://neuralensemble.org/docs/PyNN/index.html)
- [SpiNNaker](http://apt.cs.manchester.ac.uk/projects/SpiNNaker/)
- [EBRAINS](https://ebrains.eu/)
- [The Human Brain Project](https://www.humanbrainproject.eu/en/)
