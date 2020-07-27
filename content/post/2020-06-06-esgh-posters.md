---
date: 2020-06-06T00:14:57+00:00
title: El equipo de Kanteron Systems presenta 2 posters en el congreso anual de la Sociedad Europea de Genética Humana
tags: ["kanteron", "producto", "eventos"]
image: "https://aegh.org/wp-content/uploads/2020/01/2020-ESHG-Banner-850x170.jpg"
comments: true     # set false to hide Disqus comments
share: true        # set false to share buttons
thumbnailImagePosition: right
thumbnailImage: https://2020.eshg.org/wp-content/uploads/2016/10/eshg_logo.png
coverImage: https://aegh.org/wp-content/uploads/2020/01/2020-ESHG-Banner-850x170.jpg
metaAlignment: center
coverMeta: out

---

El departamento de Bioinformática de Kanteron Systems, en colaboración con científicos de varias instituciones (como la Universidad de Cambridge, o Genomics England), presenta 2 trabajos en el congreso anual de la Sociedad Europea de Genética Humana [ESHG20](https://2020.eshg.org/) que iba a celebrarse en Berlín (Alemania) pero debido a CoViD19 se celebra online, del 06-09 de junio de 2020.

<!--more-->

![ESHG](https://upload.wikimedia.org/wikipedia/commons/a/a3/Westend_CityCube_Berlin.JPG)

Dirigidos por el Dr. Pablo Marín, junto con otros miembros de su equipo como el matemático doctorando Josemi Juanes, el científico de datos Pedro Pons y el bioinformático Rodiel Martinez, los 2 posters científicos que se presentan en ESHG20 son:

* **Medical Genomics Visualization CNV "MGvizCNV": a QC Machine Learning approach for CNV evidence scoring**

**Background**: Copy Number Variants (CNV) are differentiating events between individual genomes and play an important role in cancer and mendelian diseases like neurodegenerative diseases. The current CNV detection methodologies using Next Generation Sequencing (NGS) are based mainly on measuring the relative losses or gains of the reads coverage for a genome region. However, read counts usually present various types of random noise and biases, which need to be mitigated in order to accurately analyze copy numbers. Currently there is no consensus yet on methodologies or thresholds to use for accurately calling CNVs, resulting in many different tools calling too many CNV candidates with little concordance between their results.

**Description**: Here we evaluate different signal processing techniques (including novel Machine Learning methods) for data normalization and denoising. This work employs several techniques such as wavelet shrinkage denoising and total variation denoising to smoothen readcount data while preserving high frequency information such as breakpoints, and uses a principal component analysis and expectation-maximization based technique to reduce undesired biases between samples. The log2ratio is then segmented via CBS and fused lasso techniques.

**Conclusions**: This work features a machine learning layer to clusterize a given sample with similar individuals and detect CNVs as anomalies that deviate from the assigned population, following a statistical approach that allows the user to select a desired sensitivity level for detection. We have created a workflow for CNV assessment and implemented a web application for exploring and annotating the complexity of CNV detection.

* **PanelMaps: a decision support system web application for clinical CNA evaluation**

**Background**: Current large-scale clinical genomics studies consisting of ten of thousands of whole genome sequences require a platform with the ability to analyze billions of unique variants over hundreds of terabytes of data.

**Description**:
OpenCGA, part of OpenCB suite, is a specialized open-source project that implements a high-performance, scalable and secure platform for genomic data analysis and visualisation  based on current big data technologies such as Hadoop, Spark, MongoDB or Solr. It implements an advanced analytical variant storage engine that can index and aggregate thousands of whole genomes a day and allows real-time queries, aggregations, quality control and genomic analysis on them. It can also store variant annotation and precompute cohort stats. An analytical component is implemented to allow researchers to query and execute different built-in analysis such as clinical interpretation analysis or GWAS using federation. OpenCGA implements a Catalog database to keep track of users, metadata, permissions, clinical data, QC, etc.

**Conclusions**:
OpenCGA is used as a data platform at Genomics England and other big genomics institutions, and is also available at Microsoft Azure. OpenCGA has proven to scale and perform very well to nearly 100,000 whole genomes accounting for 584 million aggregated variants or 40TB of data. In addition, it implements a rich RESTful web service API and and a client command line in different languages. Users can also use the Interactive Variant Analysis (IVA) browser to analyse and visualise biological information from various data sources.


En Kanteron Systems estamos orgullosos del trabajo de investigación y desarrollo que nuestro departamento de Bioinformática está produciendo, en colaboración con otras instituciones, y de manera abierta. Esta investigación luego se convierte, con la ayuda de nuestro departamento de Desarrollo de Software, en soluciones de Medicina de Precisión disponibles para médicos de todo el mundo.

¡Buen trabajo, equipo!
