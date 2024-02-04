# Supervised learning approaches for gut cell annotation

Repository with code for my research project for CSE 527: Computational Biology - Explainable AI in Biology & Biomedicine. My project evaluated the strengths of different supervised learning approaches on cell type annotation for gut cells.

Cell type annotation based on single-cell RNA-seq data is a critical step for further research on disease and medicine [(Yang *et al*)](https://doi.org/10.1038/s42256-022-00534-z), and supervised learning methods have shown great promise in recent years towards this goal. Evaluating the performance of different methods on new datasets is important to see their abilities to generalize. In this project, I applied various supervised learning methods for single cell annotation to gut cell data. I focused on gut cells because they are traditionally understudied – finding better ways to identify them would help lay the groundwork for future gut health research, which is more important than ever as the prevalence of gut diseases rises [(Hills *et al*)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6682904/).

## Code

The Jupyter notebooks, under `~/code`, were originally run in Google Colab. Each notebook represents a training and testing pipeline for the combination of a certain dataset and supervised learning method. Results and charts will be generated and saved. Make sure to mount your Google Drive before running the notebooks in Colab.

## Datasets

The publicly available [Space-Time Gut Cell Atlas](https://www.gutcellatlas.org/), presented in ["Cells of the human intestinal tract mapped across space and time"](https://www.nature.com/articles/s41586-021-03852-1) by Elmentaite *et al*, was used in this project. The following datasets must be downloaded to a datasets folder in order to run the code:

[Raw H5AD Data: B cells](https://cellgeni.cog.sanger.ac.uk/gutcellatlas/Bcell_raw_counts02_v2.h5ad)

[Raw H5AD Data: Myeloid](https://cellgeni.cog.sanger.ac.uk/gutcellatlas/myeloid_raw_counts02_v2.h5ad)

## Reports

See the [project report](project_report.pdf) and the [presentation poster](poster.pdf) for information on the research methodology and results.
