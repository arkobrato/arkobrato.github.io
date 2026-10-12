---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download a copy of my CV (.pdf)]({{ base_path }}/files/Arkobrato_Gupta_Vitae.pdf)

Education
======
* Ph.D. in Biostatistics, The Ohio State University, GPA: 3.88/4.0, Aug 2021 - Aug 2027 (expected)
  * Ph.D. Candidate since Jan 2026
  * Advisor: Dr. Dongjun Chung
  * Dissertation: Statistical Frameworks for Integrating Multi-Omics & Multi-modal Data
  * Coursework: Advanced Survival Analysis, Statistical Genetics, Causal Inference, Bayesian Inference, MCMC, Bioinformatics & Machine Learning in Omics
* M.S. in Statistics, The Ohio State University, Aug 2021 - Dec 2025
* M.S. in Statistics, Hindu College, University of Delhi, Jul 2017 - Jun 2019
* B.S. (Hons.) in Statistics, St. Xavier's College, University of Calcutta, Jul 2014 - Jun 2017
  * Supervisor: Durba Bhattacharya
  * Thesis: Application of Bayesian hierarchical modeling in astro-statistics — fit a Bayesian hierarchical Poisson change-point model to Chandra X-ray flare data from young stars using hybrid Gibbs/Metropolis-Hastings MCMC in R

Research Experience
======
[See full details on the Experience page →](/experience/)
  <ul>{% for post in site.experience reversed %}
    {% if post.category == "research" %}
    {% include archive-single-role-cv.html %}
    {% endif %}
  {% endfor %}</ul>

Industry Experience
======
  <ul>{% for post in site.experience reversed %}
    {% if post.category == "industry" %}
    {% include archive-single-role-cv.html %}
    {% endif %}
  {% endfor %}</ul>

Skills
======
* Clinical & Regulatory: CDISC (SDTM, ADaM, TFL), Phase I-III trial programming, survival analysis, causal inference, mixed models
* Omics & Genomics: Seurat, DESeq2, Cell Ranger & Space Ranger (10x Genomics), PLINK (GWAS), SingleR, UCell, ScType, spatial transcriptomics, TCR-seq, DNA methylation
* Statistics & Machine Learning: Bayesian inference, MCMC, FDR control, deep learning, feature selection, Gaussian mixture models
* Programming & Software: R (Shiny, R Markdown, Quarto), SAS, LaTeX, VS Code; also C, C++, Stata, SPSS, SQL

Publications
======
Peer-reviewed papers (* joint first authors)
  <ul>{% for post in site.publications reversed %}
    {% if post.category == "manuscripts" %}
    {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>

Preprints
  <ul>{% for post in site.publications reversed %}
    {% if post.category == "preprints" %}
    {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>

Manuscripts in preparation
* Gupta, A., et al. SRT: A statistical framework for the integrative analysis of spatial TCR-seq & spatial transcriptomics data. *In preparation.*
* Gupta, A., et al. SCOPE: an interactive application for Bayesian stochastic block model clustering. *In preparation.*

Presentations
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Departmental & lab talks
* Student seminar talks (4), Department of Statistics, The Ohio State University
* Research presentations at collaborating laboratories (multiple)
* Training talk on graph neural networks (GNNs), Biomedical Informatics Shared Resource (BISR), The Ohio State University Comprehensive Cancer Center, James (2025)

Teaching Experience
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Professional Memberships
======
American Statistical Association (ASA); Eastern North American Region of the International Biometric Society (ENAR); Institute of Mathematical Statistics (IMS); American Public Health Association (APHA)

Awards & Scholarships
======
* Graduate Career Accelerator Fund (CAF) Award, The Ohio State University, May 2026
* MBSW Student Travel Grant, May 2026
* Koch Graduate Student Travel Award, The Ohio State University, Mar 2026
* ICSA Student Travel Grant, Oct 2023
* INSPIRE SHE Scholarship, Department of Science & Technology, Govt. of India (top 1 percentile, 5-year award), 2014 - 2019

Research Group Activities
======
* Immuno-Oncology Informatics Group (IOIG), Pelotonia Institute (2024 - 2025) — contributed to the institute's immuno-oncology research services through data analysis, statistical consultation, and training; presented project updates at monthly group meetings
* Chung Research Group, The Ohio State University — regularly presented at lab meetings, giving detailed updates on research progress, reviewing relevant literature, and leading discussions among lab members

Leadership & Service
======
[See full details on the Leadership page →](/leadership/)
  <ul>{% for post in site.leadership reversed %}
    {% include archive-single-role-cv.html %}
  {% endfor %}</ul>

Mentoring
======
* Graduate admissions mentoring (2022 - Present) — mentored six students through the PhD admissions process and advised others applying to graduate programs; currently mentoring a student from Denison University applying to PhD programs
* Statistical mentoring for graduate researchers — guided 3 graduate researchers on statistical concepts and on designing and carrying out the analyses for their research: an MDS candidate in oral and maxillofacial surgery (through her thesis defense), and PhD students in epidemiology and computational linguistics
* Mentor, DecodingCOVID Virtual Hackathon, South Asian Medical Students' Association (2020)

Software
======
* **SCOPE**: R Shiny app for Bayesian stochastic block model clustering with posterior uncertainty quantification; used by 5+ labs in the USA, Italy, and the UK. [chunglab.bmi.osumc.edu/SCOPE](https://chunglab.bmi.osumc.edu/SCOPE)
* **SRT**: Statistical framework for integrating spatial TCR-seq and transcriptomics data

Volunteer Work
======
* Volunteer, Florence Nightingale Day for Statistics and Data Science, The Ohio State University (2023) — supported an outreach event introducing middle- and high-school students to statistics and data science, held in partnership with the American Statistical Association and the Caucus for Women in Statistics
* Volunteer, National Service Scheme (NSS) (2016) — organized games and food stalls at Shishu Mela 2016, a recreational fair for underprivileged children who traveled from villages across West Bengal
* Core Committee Member, Publication Committee, *Prakarsho* (2016) — helped produce the annual magazine of the Department of Statistics, St. Xavier's College, Kolkata

References
======
Available upon request.
