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
* May 2022 - May 2026: Graduate Research Associate
  * The Ohio State University Comprehensive Cancer Center, Pelotonia Institute for Immuno-Oncology
  * **Dissertation research**
    * **SRT**: statistical framework for integrating spatial TCR-seq and spatial transcriptomics — combines earth-mover's distance with Gaussian-mixture FDR control; identified 878 genes coupled with T-cell clonal diversity in glioblastoma, enabling biomarker discovery in the tumor microenvironment
    * **Opioid use disorder** (with multi-site collaborators) — developed a Bayesian stochastic block model clustering framework for 900+ genetically diverse rats; classified heroin-use-disorder vulnerable, intermediate, and resilient phenotypes and revealed sex-specific subgroups within the vulnerable phenotype; extending the framework to link behavioral subgroups with brain-region gene expression
    * **SCOPE**: R Shiny app implementing this clustering framework, with modularity-initialized Gibbs sampling and posterior uncertainty quantification; adopted by 5+ labs in the USA, Italy, and the UK
    * **graph-GPA 2.0** (co-first author; *Frontiers in Genetics*, 2023) — co-developed a Bayesian graphical model integrating GWAS summary statistics across multiple diseases with functional annotation data; improved detection of disease-associated variants and estimation of genetic relationships among diseases; applied to five autoimmune diseases and five psychiatric disorders
  * **Collaborative projects**
    * **DNA methylation** (co-first author; *Scientific Reports*, 2025) — co-led a genome-wide EWAS (Illumina EPIC; 802,978 CpGs; n = 324 postmenopausal women) identifying 736 differentially methylated loci between Native Hawaiian and White women, associated with liver disease pathways (61% of genes), DASH diet adherence, and adiponectin
    * **Epigenetic aging in lung cancer** (Beating Lung Cancer in Ohio study, 2025) — estimated epigenetic age and age acceleration (Horvath, PhenoAge, GrimAge) from EPIC methylation data in advanced NSCLC; showed age-acceleration estimates were robust to methylation QC (paired t-tests, correlation analysis)
    * **Comparative oncology** (*Cancers*, 2025) — performed statistical analyses of clinical, histopathologic, and gene expression data from 75 dogs with soft tissue sarcoma; higher FOXP3+ regulatory T-cell infiltration was associated with shorter progression-free intervals; tumors resembled human undifferentiated pleomorphic sarcoma, supporting canine sarcoma as a preclinical model
    * **Glioblastoma myeloid landscape** (supported a grant application, 2025) — analyzed public glioblastoma scRNA-seq data (100,000+ cells) to annotate six myeloid populations using Seurat, ScType, SingleR, and gene-signature scoring; profiled immune checkpoint ligand expression (e.g., VISTA, PD-L1, TIM-3) across myeloid subsets

* Aug - Sep 2018: Research Intern
  * Indian Institute of Management (IIM) Ahmedabad, India
  * Collaborated with a multidisciplinary team to quantify public support for nuclear energy using survey data and regression analysis

* Jun - Jul 2018: Research Intern
  * National Sample Survey Office (NSSO), Govt. of India, Kolkata, India
  * Analyzed national sample survey data using logistic regression and survey methods to identify determinants of catastrophic health expenditure in India; presented findings to the Ministry

Industry Experience
======
* Summers 2025 & 2026: Biostatistics Intern
  * Abbott Nutrition, Columbus, OH
  * 2025: Analyzed a propensity-matched NHANES cohort (n = 6,508; 2011-2018): adults consuming ≥1.2 g/kg/day protein had 1.2% greater lean soft tissue (p < 0.001), independent of physical activity, supporting protein guidelines for healthy aging. Owned the full analysis lifecycle: cohort definition, statistical method selection, confounder adjustment, and inference. Communicated results to scientific stakeholders and presented to leadership. Accepted for poster presentation at ICFSR 2026 (Washington, DC)
  * 2026: Conducted an individual participant data (IPD) meta-analysis of 14 clinical trials using both two-stage and one-stage (mixed-effects) approaches, and explored mixture models to capture heterogeneity in intervention effects on key health outcomes. Communicated results to scientific stakeholders and presented to leadership

* Aug 2019 - Jul 2021: Statistical Programmer
  * Novartis Healthcare Pvt. Ltd., Hyderabad, India
  * Programmed SDTM and ADaM datasets and tables, listings, and figures (TFLs) in SAS and R to CDISC standards for three clinical trials, including the pivotal Phase III study of Kisqali (ribociclib) in breast cancer
  * Provided statistical programming support for early-phase studies with the Novartis Institutes for BioMedical Research (NIBR)
  * Implemented the statistical methods specified in statistical analysis plans (SAPs), working with trial statisticians on analysis specifications and outputs
  * Performed independent double programming and quality-control validation of datasets and outputs to ensure accuracy and submission readiness
  * Built reporting databases supporting regulatory submissions across solid-tumor oncology and respiratory therapeutic areas

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
* Student Representative, Columbus Chapter, American Statistical Association (ASA), 2026 - 2027
* President, Statistics & Biostatistics Graduate Student Association, The Ohio State University, Aug 2024 - Aug 2025 — led a 100+ member organization; liaised between graduate students and department administration
* Officer, Public Health Graduate Student Association (PHGSA), The Ohio State University, Aug 2022 - Aug 2023 — served as an officer of the graduate student association for the College of Public Health
* Placement Coordinator, Department of Statistics, University of Delhi, Jan 2018 - Jun 2019 — coordinated full-time placements for 70+ students and internships for 70+ students; invited, hosted, and communicated with recruiting companies, and helped train students for the recruitment process
* Judge, Statistical Analysis Award, State Science Day, Ohio Academy of Science, 2026 — evaluated student science-fair projects for the award sponsored by the Department of Statistics, The Ohio State University
* Head Evaluator, FRAME Summer Fellowship, West Bengal — led the evaluation of applications for FRAME (Fellowship for Research, Academic Mentorship and Exploration)

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
**Dongjun Chung, PhD**
Professor, Department of Biomedical Informatics, College of Medicine
The Ohio State University, Columbus, OH
Dongjun.Chung@osumc.edu
