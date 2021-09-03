GSoC 2021 Implementing multiple clustering algorithms and dimensionality reduction techniques on clusterMaker2

## Main repo: https://github.com/RBVI/clusterMaker2

## Contributions:
7 JUNE - 23 AUGUST 2021 Google Summer of Code by Maija Utriainen

Implementing remote dimensionality reduction techniques using similar approach to last years remote network clusterers (see below).

Dimensionality reduction techniques added: Isomap, Local Linear Embedding, MDS, Spectral, tSNE, UMAP
Changes to ClusterJobExecutionService and RemoteServer: abstracting and replacing code to another class
Subclasses to ClusterJobHandler specific to network clusterers and dimensionality reduction techniques
The new algorithms registered in CyActivator
