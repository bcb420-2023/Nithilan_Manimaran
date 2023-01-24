FROM risserlin/bcb420-base-image:winter2023

RUN R -e "BiocManager::install('DESeq2')"

RUN install2.r \
    -d TRUE \
    -r 'https://cran.rstudio.com' \
    pheatmap
