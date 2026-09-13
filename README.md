# R 3D Scatter Plot — Mariana Trench Geomorphic Factors

R script drawing a three-dimensional scatter plot of three geomorphic factors of the Mariana Trench (z, x, y axes), coloured by category, to visualise their joint distribution in 3-D space.

## Related publication

Lemenkova, P. Statistical Analysis of the Mariana Trench Geomorphology Using R
Programming Language. Geodesy and Cartography 2019, 45(2), 57-84.

- DOI: https://doi.org/10.3846/gac.2019.3785
- figshare: https://doi.org/10.6084/m9.figshare.9762860
- HAL: https://hal.science/hal-02277500
- Zenodo: https://zenodo.org/record/3385005
- ISSN: 2029-6991 (Scopus)

(This 3D scatter is not a numbered figure in that paper; this repository is a companion visual using the same Mariana Trench data.)

## Script

- scatter_3d_zxy.R: reads Morphology.csv and draws a 3D scatter plot of three factors with per-category colouring (scatterplot3d / plot3D).

## Methods

- Three-dimensional scatter plotting of multivariate categorical data.

## Data

- Morphology.csv: per-profile geomorphic factors of the Mariana Trench.

## Requirements

- R (>= 3.5); packages: scatterplot3d (or plot3D)

## Author and citation

Polina Lemenkova — ORCID https://orcid.org/0000-0002-5759-1089

Cite: Lemenkova, P. Statistical Analysis of the Mariana Trench Geomorphology Using R Programming Language. Geodesy and Cartography 2019, 45(2), 57-84. https://doi.org/10.3846/gac.2019.3785

## License

MIT — see LICENSE (Copyright Polina Lemenkova).
