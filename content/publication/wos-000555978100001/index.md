---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'A systematic comparison of pharmacogene star allele calling bioinformatics
  algorithms: a focus onCYP2D6genotyping'
subtitle: ''
summary: ''
authors:
- David Twesigomwe
- Galen E. B. Wright
- Britt I. Drogemoller
- Jorge da Rocha
- Zane Lombard
- Scott Hazelhurst
tags: []
categories: []
date: '2020-08-01'
lastmod: 2022-12-11T16:52:15-06:00
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
publishDate: '2022-12-11T22:52:15.433258Z'
publication_types:
- '2'
abstract: Genetic variation in genes encoding cytochromeP450enzymes has important
  clinical implications for drug metabolism. Bioinformatics algorithms for genotyping
  these highly polymorphic genes using high-throughput sequence data and automating
  phenotype prediction have recently been developed. TheCYP2D6gene is often used as
  a model during the validation of these algorithms due to its clinical importance,
  high polymorphism, and structural variations. However, the validation process is
  often limited to common star alleles due to scarcity of reference datasets. In addition,
  there has been no comprehensive benchmark of these algorithms to date. We performed
  a systematic comparison of three star allele calling algorithms using 4618 simulations
  as well as 75 whole-genome sequence samples from the GeT-RM project. Overall, we
  found that Aldy and Astrolabe are better suited to call both common and rare diplotypes
  compared to Stargazer, which is affected by population structure. Aldy was the best
  performing algorithm in callingCYP2D6structural variants followed by Stargazer,
  whereas Astrolabe had limitations especially in calling hybrid rearrangements. We
  found that ensemble genotyping, characterised by taking a consensus of genotypes
  called by all three algorithms, has higher haplotype concordance but it is prone
  to ambiguities whenever complete discrepancies between the tools arise. Further,
  we evaluated the effects of sequencing coverage and indel misalignment on genotyping
  accuracy. Our account of the strengths and limitations of these algorithms is extremely
  important to clinicians and researchers in the pharmacogenomics and precision medicine
  communities looking to haplotypeCYP2D6and other pharmacogenes using high-throughput
  sequencing data.
publication: '*NPJ GENOMIC MEDICINE*'
doi: 10.1038/s41525-020-0135-2
---
