# Single cell RNA-seq and ATAC seq analysis of cardiac progenitor cell transition states and lineage settlement



### RNA-seq analysis

#### R session information

For requirements, please see the file `RNA-seq_sessionInfo.txt` for specific R packages and their versions.

#### Preprocessing

R code to preprocess single-cell RNA-seq data from scratch can be found in the `src` directory. Steps (e.g. *quality control*, *filtering*, *normalization*, etc.) should be run in the order indicated by the leading counter in the filename (e.g. `00_filtering.R` before `01_normalisation.R`)

#### Figures

We additionally provide scripts to reproduce most of the main figures. The R code can be found in the `figure_src` directory and is split into individual files. Figures can be recreated without the need of *preprocessing* the data.

### Citation

Please refer to the following research article when using data from this repository:

Jia G, Preussner J, Chen X, Guenther S, Yuan X, Yekelchyk M, Kuenne C, Looso M, Zhou Y, Teichmann S and Braun T. Single cell RNA-seq and ATAC seq analysis of cardiac progenitor cell transition states and lineage settlement. **Nature Communications** (*2018*), *tba*.
