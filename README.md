# common-gene-signature

Find common gene signatures for two different types of cancer: breast invasive carcinoma and prostate adenocarcinoma.

Two datasets were extracted from the Cancer Genome Atlas (TCGA) database, using the tcga.data R package (https://github.com/averissimo/tcga.data): the BRCA RNA-Seq Fragments Per Kilobase per Million (FPKM) dataset and the PRAD RNA-Seq Fragments Per Kilobase per Million (FPKM) dataset.

The BRCA gene expression data is composed of 57251 variables for a total of 1222 samples from 1097 individuals. From those samples, 1102 presented with primary solid tumours, 7 with metastases, and 113 with normal breast tissue.

The PRAD gene expression data is composed of 57035 variables for a total of 551 samples from 500 individuals. From those samples, 498 presented with primary solid tumours, 1 with metastases, and 52 with normal prostate tissue.
