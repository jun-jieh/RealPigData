**Heuristic hyperparameter optimization of deep learning models for genomic prediction**

__Junjie Han, Cedric Gondro, Kenneth Reid & Juan P. Steibel__

If you find this resource helpful, please cite:

[J Han, C Gondro, K Reid, JP Steibel. 2021. Heuristic hyperparameter optimization of deep learning models for genomic prediction. G3 Genes|Genomes|Genetics](https://academic.oup.com/g3journal/advance-article/doi/10.1093/g3journal/jkab032/6129776/)

This repository includes the real pig dateset used for DE_DL. To find the code for implementing differential evolution on top of multilayer perceptron and convolutional neural network, please refer to this repository: https://github.com/jun-jieh/DE_DL




## Genotype

Genotype.RData contains the genotypes (M=28,916 for SNP markders) for 910 F2 pigs (N=910). If the file is loaded correctly, there should be an object named "geno" in the R environment.

## Adj_ph

Adj_ph.RData contains the adjusted ph value measured 24 hours after slaughter. If the file is loaded correctly, there should be an object named "y" in the R environment.

