# ddqcR - An updated fork
Adapted from: https://github.com/ayshwaryas/ddqc

- Updated ddqc.metrics to:
  - Plot ribo
  - Default do.ribo = TRUE
  - Option to set ribo cutoff filter, percent.ribo.upper.bound = 60
- Adjusted initialQC to nGenes = 50, mito = 60, ribo = 60

## Required R verison >= 4.0.0
## Required packages
- Seurat (>= 4.0.0),
- ggplot2 (>= 3.3.0)
## installation
Use the following command to install the package:
`devtools::install_github("halterc/ddqc_R")`
