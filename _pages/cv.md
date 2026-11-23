---
title: "Curriculum vitae"
permalink: /curriculum-vitae/
author_profile: true
redirect_from:
  - /resume
---

## Education

- **North Carolina State University**. Ph.D. in Bioinformatics, co-major in Statistics. August 2021–December 2026 (expected).
- **Jiangnan University**. M.Eng. in Food Science and Engineering. August 2017–August 2020.
- **Jiangnan University**. B.Eng. in Food Science and Engineering. September 2014–June 2017.

## Research interests

Phylogenetics and phylodynamics, Bayesian hierarchical and spatial modeling, simulation-based inference and uncertainty quantification, statistical genomics, and infectious disease and evolutionary dynamics.

## Experience

- **Graduate Research Assistant, North Carolina State University**. August 2022–present. Develop statistical models and reproducible workflows for evolutionary and biomedical research using high-performance computing.
- **Teaching Assistant, Department of Statistics, North Carolina State University**. Fall 2025 and Fall 2026. Supported graduate courses in Bayesian inference, ecological statistics, and statistical methods. [Teaching details]({{ '/teaching/' | relative_url }}).
- **Algorithm Intern, Illuminera**. November 2020–March 2021. Analyzed mobile-app interaction data and built a screenshot key-frame extraction pipeline using SQL and PySpark.
- **Bioinformatics Analyst Intern, Jiaofu Biomedical Technology Science Company**. December 2017–February 2018. Analyzed RNA sequencing data, ran differential expression and gene set enrichment analyses, and built gene–lncRNA correlation networks.

## Publications

<ul>
{% for publication in site.publications reversed %}
  <li><a href="{{ publication.url | relative_url }}">{{ publication.title | escape }}</a>. <i>{{ publication.venue | escape }}</i>, {{ publication.publication_year }}{% if publication.category == 'preprints' %} (preprint){% endif %}.</li>
{% endfor %}
</ul>

[View the publications page for full citations and DOI links.]({{ '/publications/' | relative_url }})

## Conference presentations

Presented at Joint Statistical Meetings, the Ecology and Evolution of Infectious Diseases Conference, and the Genetics, Genomics, and Bioinformatics Research Symposium. [Presentation details]({{ '/talks/' | relative_url }}).

## Technical skills

- **Programming and computing.** Python, R, SQL, SAS, PySpark, Linux/Bash, Git, and high-performance computing.
- **Statistical modeling.** Bayesian hierarchical models, MCMC, Gaussian processes, splines, simulation-based inference, and longitudinal, time-series, and survival analysis.
- **Scientific computing and genomics.** JAX, NumPyro, PyTorch, BayesFlow, BEAST2, comparative genomics, metagenomics, and RNA-seq analysis.

## Training and honors

- Taming the BEAST workshop in Bayesian phylogenetics, Squamish, British Columbia, 2023.
- Mu Sigma Rho, National Statistics Honorary Society, member since 2023.
- Honored Student, Jiangnan University, top 4% of undergraduates.
- University Debate Champion and Best Debater, Jiangnan University, 2015–2016.
- National Scholarship, Jiangnan University, 2014–2015.
