Bootstrap: docker
From: rocker/verse:4.0.0

%post

        R -e 'install.packages(c("BiocManager","lme4","multcomp","reshape2","circlize","MASS","mice","survival","stats","RhpcBLASctl","uwot"), verbose=FALSE, quiet=TRUE)'

        R -e 'BiocManager::install(version="3.12",ask=FALSE);BiocManager::install(c("flowCore","FlowSOM","SummarizedExperiment","S4Vectors", "limma","edgeR","ComplexHeatmap","BiocParallel","BiocStyle", "CATALYST"), ask = FALSE, verbose=FALSE, quiet=TRUE)'


