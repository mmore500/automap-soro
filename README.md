# automap-soro

This project is based on AutoMap, a pair of methods for automatic generation of evolvable genotype-phenotype mappings.
Both use an artificial neural network autoencoder trained on phenotypes harvested from fitness peaks as the basis for a genotype-phenotype mapping.
In the first, the decoder segment of a bottlenecked autoencoder serves as the genotype-phenotype mapping.
In the second, a denoising autoencoder serves as the genotype-phenotype mapping.

The technique was introduced in

> Matthew Andres Moreno, Wolfgang Banzhaf, and Charles Ofria.
"Learning an Evolvable Genotype-Phenotype Mapping."
Proceedings of the Genetic and Evolutionary Computation Conference.
ACM, 2018.

You can find the paper and supporting materials at [https://osf.io/n92c7/](https://osf.io/n92c7/).

The project was built using the [evosoro](https://github.com/skriegman/evosoro) soft robot simulator.
Evosoro was designed and developed by the [Morphology, Evolution & Cognition Laboratory](http://www.meclab.org), University of Vermont.
The library is built on top of the open source [VoxCAD](https://github.com/jonhiller/VoxCAD) and the underlying voxel physics engine ([Voxelyze](https://github.com/jonhiller/Voxelyze)) which were both developed by the [Creative Machines Lab](http://www.creativemachineslab.com/), Columbia University.

## *TODO*

Experiments reported in this paper used [vTODO](https://github.com/mmore500/automap-soro/tree/vTODO) of this software.

data, tutorials, and writeup @ [https://osf.io/6jf52/](https://osf.io/6jf52/)

> TODO

## Software Authorship

Matthew Andres Moreno

`mmore500@msu.edu`
