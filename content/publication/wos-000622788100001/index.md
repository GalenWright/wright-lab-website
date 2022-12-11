---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'StellarPGx: A Nextflow Pipeline for Calling Star Alleles in Cytochrome P450
  Genes'
subtitle: ''
summary: ''
authors:
- David Twesigomwe
- Britt I. Drogemoller
- Galen E. B. Wright
- Azra Siddiqui
- Jorge da Rocha
- Zane Lombard
- Scott Hazelhurst
tags: []
categories: []
date: '2021-09-01'
lastmod: 2022-12-11T16:52:13-06:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-12-11T22:52:13.382676Z'
publication_types:
- '2'
abstract: Bioinformatics pipelines for calling star alleles (haplotypes) in cytochrome
  P450 (CYP) genes are important for the implementation of precision medicine. Genotyping
  CYP genes using high throughput sequencing data is complicated, e.g., by being highly
  polymorphic, not to mention the structural variations especially in CYP2D6, CYP2A6,
  and CYP2B6. Genome graph-based variant detection approaches have been shown to be
  reliable for genotyping HLA alleles. However, their application to enhancing star
  allele calling in CYP genes has not been extensively explored. We present StellarPGx,
  a Nextflow pipeline for accurately genotyping CYP genes by combining genome graph-based
  variant detection, read coverage information from the original reference-based alignments,
  and combinatorial diplotype assignments. The implementation of StellarPGx using
  Nextflow facilitates its portability, reproducibility, and scalability on various
  user platforms. StellarPGx is currently able to genotype 12 important pharmacogenes
  belonging to the CYP1, 2, and 3 families. For purposes of validation, we use CYP2D6
  as a model gene owing to its high degree of polymorphisms (over 130 star alleles
  defined to date, including complex structural variants) and clinical importance.
  We applied StellarPGx and three existing callers to 109 whole genome sequenced samples
  for which the Genetic Testing Reference Material Coordination Program (GeT-RM) has
  recently provided consensus truth CYP2D6 diplotypes. StellarPGx had the highest
  CYP2D6 diplotype concordance (99%) with GeT-RM compared with Cyrius (98%), Aldy
  (82%), and Stargazer (84%). This exemplifies the high accuracy of StellarPGx and
  highlights its importance for both research and clinical pharmacogenomics applications.
  The StellarPGx pipeline is open-source and available from .
publication: '*CLINICAL PHARMACOLOGY & THERAPEUTICS*'
doi: 10.1002/cpt.2173
---
