# Introduction

## Introduction

### Background

**CMD Somatic Panel Pipeline** is a nextflow based clinical bioinformatics pipeline.The pipeline takes raw sequencing files as _fastq.gz_ from _samplesheet.csv_ along with other meta data among others - sample type, sex, number of reads etc. The pipeline is intended to run in CMD high performance clusters (grace or hopper) along with all the references files in the config file. The results produced by the pipelines are visualized and reported in in-house interpretation and visualization tools.

To start the pipeline in command line simply run as

```console
 $ nextflow run main.nf -entry SPP -c nextflow.hopper_test.config --csv Sample.csv -profile solid,hg38

```

### TODOs
