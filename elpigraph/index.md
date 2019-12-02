# ElPiGraph

ElPiGraph (Elastic Principal Graph) is a method for approximating datasets with complex topologies.

This directory contains codes, example datasets, and analyses centered on the application of ElPiGraph to different types of data.

![alt ElPiGraph reconstructions](./images/elpigraph_image.jpg)

## ElPiGraph implementations (from most to least complete)

[ElPiGraph.R](https://github.com/sysbio-curie/ElPiGraph.R) - implementation of ElPiGraph in R (most complete functionality and multi-core support)

[ElPiGraph.P](https://github.com/j-bac/elpigraph-python) - implementation of ElPiGraph in Python (Equivalent to R version, multi-core and GPU support. Missing some of the plotting functionalities)

[ElPiGraph.M](https://github.com/sysbio-curie/ElPiGraph.M) - implementation of ElPiGraph in MATLAB (Less options than Python and R version)

[ElPiGraph.Java](https://github.com/auranic/VDAOEngine/) - implementation of ElPiGraph as part of the VDAO engine

[ElPiGraph.Scala](https://github.com/mraad/elastic-graph) - implementation of ElPiGraph in Scala


## Notebooks (containing code and figures)

[Branching pseudotime reconstruction from Nestorowa et la. with MLLE](roscoff_sct_nesto_mlle/index.html)

[Branching pseudotime reconstruction from Nestorowa et la. with PCA](roscoff_sct_nesto_pca/index.html)

[Linear pseudotime reconstruction from Schlitzer et la. with MLLE and PCA](roscoff_sct_schli_mlle_pca/index.html)

## Figures

[3D Force directed layout derived for xenopus stage 22 embryos](xeno_k5_fd/index.html) - Interactive figure (see Albergante et al, 2018 for details)

[3D Force directed layout with the fitted consensus graph for xenopus stage 22 embryos](xeno_k5_consensus/index.html) - Interactive figure (see Albergante et al, 2018 for details)


## References

[Albergante et al, Robust and scalable learning of data manifolds with complex topologies via ElPiGraph, 2018, preprint](https://arxiv.org/abs/1804.07580)

[Gorban A, Sumner N, Zinovyev A. Topological grammars for data approximation. 2007. Applied Mathematics Letters 20(4), 382-386](https://www.sciencedirect.com/science/article/pii/S0893965906001856)

[Gorban A.N, Zinovyev A. Principal manifolds and graphs in practice: from molecular biology to dynamical systems. 2010. Int J Neural Syst 20(3):219-32](https://www.worldscientific.com/doi/abs/10.1142/S0129065710002383)

[Chen H, Albergante L, Hsu JY, Lareau CA, Lo Bosco G, Guan J, Zhou S, Gorban AN, Bauer DE, Aryee MJ, Langenau DM, Zinovyev A, Buenrostro JD, Yuan G-C, Pinello L. Single-cell Trajectories Reconstruction, Exploration And Mapping of omics data with STREAM. 2019. Nature Communications 10:1903.](https://www.nature.com/articles/s41467-019-09670-4)

[Gorban A, Mirkes E, Zinovyev A. Robust principal graphs for data approximation. Archives of Data Science 2(1):1:16, 2017.](https://arxiv.org/abs/1603.06828)

[Zinovyev A. and Mirkes E. Data complexity measured by principal graphs. 2013. Computers and Mathematics with Applications 65:1471-1482.](https://www.sciencedirect.com/science/article/pii/S0898122112007055)

## Contact

[Jonathan Bac](https://github.com/j-bac)

[Luca Albergante](https://github.com/Albluca)

[Andrei Zinovyev](https://auranic.github.io)



