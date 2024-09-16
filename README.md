# README
Here's a draft README based on the provided code:

# Acute Myeloid Leukemia Heatmap Analysis

This repository contains an R script for generating a heat map of gene expression data from acute myeloid leukemia (AML) samples. The analysis adapts work originally published in Shih et al., 2017 [2].

## Software Requirements

To run this project, you'll need:

- R (version 3.0.2 or higher)
- R packages: pheatmap, magrittr, dplyr, readr, tibble, sessioninfo

These packages can be installed using the following commands:

```r
install.packages(c("pheatmap", "magrittr", "dplyr", "readr", "tibble", "sessioninfo"))
```

## Dataset Information

This analysis uses RNA-seq data from 19 AML model mouse samples obtained from [refine.bio](https://www.refine.bio/). The dataset contains gene expression profiles for AML samples under controlled treatment conditions [2].

Key points:
- 19 samples from AML model mice
- Pre-processed and quantile-normalized data
- Available at: https://www.refine.bio/experiments/SRP070849

## Project Structure

The project consists of three main directories:

- `data`: Contains input datasets
- `plots`: Stores generated heatmaps
- `results`: Saves processed data files

## Expected Outputs

The main output of this analysis is an annotated heatmap visualizing gene expression patterns across the AML samples. Specifically:

1. A PNG file named "aml_heatmap.png" in the `plots` directory
2. A TSV file named "top_90_var_genes.tsv" in the `results` directory

## Last Updated

This analysis was adapted from the original source in October 2021.

## How to Use

1. Clone this repository
2. Navigate to the project directory in your terminal/command prompt
3. Open the R script in your preferred R environment
4. Run the script to generate the heatmap and save the results

Note: This script assumes you have the necessary data downloaded from refine.bio. You'll need to download and place the data files in the `data` directory before running the script.

## References

[2] Shih, A. H., et al. (2017). IDH mutations in acute myeloid leukemia genome-wide association studies and functional experiments. Blood, 130(15), 2003–2014. doi:10.1182/blood-2017-02-76378

This README provides an overview of the project, its requirements, structure, and expected outputs. It also includes information about the dataset and references the original publication. The next step would be to add more detailed usage instructions and potentially include a brief tutorial on how to interpret the results.

Citations:
[1] https://stackoverflow.com/questions/51957921/is-it-possible-to-put-a-readme-file-for-r-code-on-github-that-displays-output
[2] https://github.com/jtleek/rpackages/blob/master/README.md
[3] https://usethis.r-lib.org/reference/use_readme_rmd.html
[4] https://bookdown.org/rdpeng/RProgDA/documentation.html
[5] https://r4ds.had.co.nz/r-markdown.html
[6] https://crd230.github.io/hw_guidelines.html
[7] https://github.com/NBISweden/development-guidelines/blob/main/README.md
[8] https://cran.r-project.org/web/packages/workflowr/vignettes/wflow-01-getting-started.html
[9] https://r-pkgs.org/release.html
[10] https://andrewmaclachlan.github.io/CASA0005repo_20192020/git-github-and-rmarkdown.html