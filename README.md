<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

# Ecoregion diversity

Here I use herbarium data from the RAINBIO and FLOTROP datasets to calculate species richness by ecoregion. Both datasets combined represent just under 1M records.
I used the ecoregions map from Olsen et al. 2017 to count points in polygons and assign an ecoregion to each records.
I then build a species x site matrix for clustering and ordination approaches as well as building a phylogeny for all of Africa using the V.Phylomaker package.

## Phylogenetic diversity

I use the `picante` package to calculate and contrast metrics of phylogenetic diversity of ech ecoregion.
