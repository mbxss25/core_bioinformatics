# core_bioinformatics

The dataset used is a benchmark dataset for the WGS analysis of SARS-CoV-2. 

The Variants of Interest/Variants of Concern (VOI/VOC) lineages study validated a lineage-calling pipeline with 16 samples from CDC-defined lineages. 

The dataset has been described in detail here: https://github.com/CDCgov/datasets-sars-cov-2

In thiswe will analyse one sample from the VOI/VOC dataset. 

Download the sequence data for this sample using the following command (the sample identifier below is the accession number for the data in the European Nucleotide Archive (ENA)):

fastq-dump --split-files ERR5743893
