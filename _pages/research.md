---
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /portfolio/
---

My research spans statistical genomics, evolutionary dynamics, and Bayesian inference for models that are expensive to simulate.

## Bayesian phylodynamics

My doctoral research with [David A. Rasmussen](https://phylodynamics.wordpress.ncsu.edu/) and [Brian J. Reich](https://bjreich.wordpress.ncsu.edu/) at NC State asks what evolutionary trees can tell us about genetic differences in fitness. A tree records how lineages branch over time. When several genetic features are inherited together, it becomes difficult to tell how much each one contributes to differences in lineage growth.

I developed BayesMFBD, a Bayesian multi-feature birth–death model that uses an evolutionary tree and genomic data to estimate associations between genetic features and lineage growth. The model estimates individual effects and interactions, including epistasis, where the effect of one feature depends on another. It quantifies how much uncertainty surrounds those estimates.

I use simulated trees with known histories to assess how accurately the model recovers individual effects and how often its credible intervals contain the true values. I vary tree size and the correlation among genetic features to learn when the estimates are reliable. I also apply the framework to existing bacterial genomic data and compare how different models estimate overall fitness and attribute effects to individual features.

[BayesMFBD on GitHub](https://github.com/LucianCen/BayesMFBD) · [Preprint](https://doi.org/10.64898/2026.10.19.760109)

## Recombination breakpoint localization

I benchmarked three methods for identifying recombination breakpoints using data with known evolutionary histories. The study examined how sequence diversity and the availability of informative sites affect localization accuracy, as well as how errors affect estimates of local evolutionary trees.

[Article in *Molecular Biology and Evolution*](https://doi.org/10.1093/molbev/msae133)

## Cardiovascular modeling

I work with [Brian J. Reich](https://bjreich.wordpress.ncsu.edu/), Mette S. Olufsen, and Charles Puelz on models of blood-flow wave propagation. I use vessel geometry from cardiovascular images and develop Bayesian and simulation-based methods to quantify uncertainty in biomechanical parameters.

## Other projects

At NC State, I analyzed publicly available fruit-fly connectome data with Christa Baker to study auditory circuits. At the University of Minnesota, I investigated diet–microbiome associations using shotgun metagenomics with Dan Knights. At Jiangnan University, I studied how *Lactobacillus plantarum* genomes vary across ecological niches with Qixiao Zhai and Wei Chen.
