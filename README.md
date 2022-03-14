# Ecoregion_diversity

Here I use herbarium data from the RAINBIO and FLOTROP datasets to calculate species richness by ecoregion. Both datasets combined represent just under 1M records.
I used the ecoregions map from Olsen et al. 2017 to count points in polygons and assign an ecoregion to each records.
I then build a species x site matrix for clustering and ordination approaches as well as building a phylogeny for all of Africa using the V.Phylomaker package.

## Phylogenetic diversity

I use the `picante` package to calculate and contrast metrics of phylogenetic diversity of ech ecoregion.
