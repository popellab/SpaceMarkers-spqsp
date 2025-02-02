<p align="center">
  <img src="SpaceMarkersHexWhite.png" width="200" title="SpaceMarkers hex logo">
</p>

# SpaceMarkers
An R/Bioconductor software tool to identify genes associated with latent space interactions in spatial transcriptomics.

## Citation
This tutorial aims to help user to apply SpaceMarkers on spatial Quantitative Pharmacology (spQSP) model. </br>
If you use the SpaceMarkers software please cite:

Atul Deshpande, Melanie Loth, et al.,
[Uncovering the spatial landscape of molecular interactions within the tumor microenvironment through latent spaces](https://doi.org/10.1101/2022.06.02.490672).
*bioRxiv* 2022. doi:10.1101/2022.06.02.490672

## Installation
You can install SpaceMarkers directly from the Github source.
```
install.packages("remotes")
remotes::install_github("FertigLab/SpaceMarkers", dependencies = TRUE, build_vignettes = TRUE)
```
## Running SpaceMarkers on spQSP outputs
The sample result for running the code is stored in <code>/sample_result </code> folder </br>
```
$ R_SCRIPT = "spQSP_SplnMarkers.R' 'sample_result'
$ Rscript $R_SCRIPT
```
