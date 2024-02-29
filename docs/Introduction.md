# Introduction


## Introduction


**CMD Somatic Panel Pipeline** is a nextflow based clinical bioinformatics pipeline.The pipeline takes raw sequencing files as *fastq.gz* from *samplesheet.csv* along with other meta data among others - sample type, sex, number of reads etc. The pipeline is intended to run in CMD high performance clusters (grace or hopper) along with all the references files in the config file. The results produced by the pipelines are visualized and reported in in-house interpretation and visualization tools.


To start the pipeline in command line simply run as

```console
  $ nextflow run main.nf -entry SPP -c nextflow.hopper_test.config --csv Sample.csv -profile solid,hg38

```


This automatic documentation generation is a time-saving tool for developers and teams, as it eliminates the need to manually create and maintain documentation. It also helps ensure that documentation is up-to-date and consistent, as changes made to the pipeline.yaml file used for the document updation in a simple and easy way. 

The pipeline.yaml file contains all the relevant information about the pipeline or tool, including the description, inputs, outputs, parameters, and usage. This information is used to generate the HTML and MD documents, which provide clear and detailed information about the pipeline or tool.

The HTML document is visually appealing and easy to navigate, with links to different sections and a search bar for quickly finding specific information. The MD document is plain text, but can be formatted with Markdown syntax for a more readable and structured format. The MD document can be uploaded to a readthedocs server for online documentation. It uses the mkdocs format, with the required "docs" folder and related files in the project root folder. 

Additionally, the generated documentation also includes a table of contents for easy navigation, and sections for examples. 

Overall, this repo helps improve the documentation process for pipelines and tools, making it easier for others to understand and use them.


