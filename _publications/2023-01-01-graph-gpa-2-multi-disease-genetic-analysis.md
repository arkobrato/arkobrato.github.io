---
title: "graph-GPA 2.0: improving multi-disease genetic analysis with integration of functional annotation data"
collection: publications
category: manuscripts
project: graph-gpa
permalink: /publication/2023-01-01-graph-gpa-2-multi-disease-genetic-analysis
excerpt: 'Co-first author. A Bayesian graphical model integrating GWAS summary statistics across multiple diseases with functional annotation data, applied to five autoimmune diseases and five psychiatric disorders.'
date: 2023-01-01
venue: 'Frontiers in Genetics'
paperurl: 'https://doi.org/10.3389/fgene.2023.1079198'
citation: 'Deng, Q.*, Gupta, A.*, Jeon, H.*, Nam, J. H., Yilmaz, A. S., Chang, W., Pietrzak, M., Li, L., Kim, H. J., &amp; Chung, D. (2023). &quot;graph-GPA 2.0: improving multi-disease genetic analysis with integration of functional annotation data.&quot; <i>Frontiers in Genetics</i>, 14. (* joint first authors)'
---
Genome-wide association studies (GWAS) often have limited power to detect disease-associated genetic variants, especially for complex diseases with many loci of small individual effect. Integrating functional annotation data (information about what a genetic variant actually does biologically) and sharing information across genetically related diseases can both improve variant detection, but existing methods struggle to do both at once.

graph-GPA 2.0 extends the original graph-GPA framework into a Bayesian graphical model that jointly analyzes GWAS summary statistics across multiple diseases while incorporating functional annotation data. The model estimates a genetic relationship network among the diseases being analyzed, borrowing statistical strength from related diseases and functional annotations to improve both the detection of disease-associated variants and the estimation of genetic relationships among diseases.

We applied graph-GPA 2.0 to five autoimmune diseases and five psychiatric disorders, demonstrating improved power to detect risk variants compared to single-disease analyses, while also characterizing the shared genetic architecture across these disease groups.

*I was co-first author on this paper, contributing to the development and implementation of the statistical framework.*
