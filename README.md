# Getting-Molecules-for-MaPhi
Based in TeachOpenCADD you will learn how to download small molecules from UniProt

This tutorial will teach you how to download small molecules from UniProt, to be used for MaPhi, it is a Jupyter notebook inspired using TeachOpenCADD https://github.com/volkamerlab/TeachOpenCADD. The exaple that here we use is for  NMDA receptor complexes that function as heterotetrameric, ligand-gated ion channels with high calcium permeability and voltage-dependent sensitivity to magnesium. Channel activation requires binding of the neurotransmitter glutamate to the epsilon subunit, glycine binding to the zeta subunit, plus membrane depolarization to eliminate channel inhibition by Mg2+.

We are going to use the results of this article https://www.sciencedirect.com/science/article/pii/S0223523409000129 in order to differentiate between agonist and antagonistusing electronic descriptor.

In order to get the necessary libraries install Maphi and follow the next instructions after installing it.


# Activate the conda environment.

```
$ conda activate maphi
```

# Link the conda environment to the Jupyter notebook.

```
$ python -m ipykernel install --user --name maphi
```


