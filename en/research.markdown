---
layout: page
lang: en
title: Research & Papers
order: 100
permalink: /en/research
---

Mateusz Chiliński, __Jakub Lipiński__, Abhishek Agarwal, Yijun Ruan, Dariusz Plewczynski

Scientific Reports volume 13, Article number: 11693 (2023)

[Enhanced performance of gene expression predictive models with protein-mediated spatial chromatin interactions](https://www.nature.com/articles/s41598-023-38865-5) [![Archived PDF](/assets/images/pdf.svg){: style="width:1em; display: inline; margin: 0 0 0rem;" }](/assets/pdf/s41598-023-38865-5.pdf)

<small>There have been multiple attempts to predict the expression of the genes based on the sequence, epigenetics, and various other factors. To improve those predictions, we have decided to investigate adding protein-specific 3D interactions that play a significant role in the condensation of the chromatin structure in the cell nucleus. To achieve this, we have used the architecture of one of the state-of-the-art algorithms, ExPecto, and investigated the changes in the model metrics upon adding the spatially relevant data. We have used ChIA-PET interactions that are mediated by cohesin (24 cell lines), CTCF (4 cell lines), and RNAPOL2 (4 cell lines). As the output of the study, we have developed the Spatial Gene Expression (SpEx) algorithm that shows statistically significant improvements in most cell lines. We have compared ourselves to the baseline ExPecto model, which obtained a 0.82 Spearman's rank correlation coefficient (SCC) score, and 0.85, which is reported by newer Enformer were able to obtain the average correlation score of 0.83. However, in some cases (e.g. RNAPOL2 on GM12878), our improvement reached 0.04, and in some cases (e.g. RNAPOL2 on H1), we reached an SCC of 0.86.</small>

[https://doi.org/10.1038/s41598-023-38865-5](https://doi.org/10.1038/s41598-023-38865-5)

<br />

Cheynna Crowley, Yuchen Yang, Yunjiang Qiu, Benxia Hu, Armen Abnousi, __Jakub Lipiński__, Dariusz Plewczyński, Di Wu, Hyejung Won, Bing Ren, Ming Hu, Yun Li,

Computational and Structural Biotechnology Journal 2020, ISSN 2001-0370

[FIREcaller: Detecting Frequently Interacting Regions from Hi-C Data](http://www.sciencedirect.com/science/article/pii/S2001037020305511)
[![Archived PDF](/assets/images/pdf.svg){: style="width:1em; display: inline; margin: 0 0 0rem;" }](/assets/pdf/1-s2.0-S2001037020305511-main.pdf)

<small>Abstract: Hi-C experiments have been widely adopted to study chromatin spatial organization, which plays an essential role in genome function. We have recently identified frequently interacting regions (FIREs) and found that they are closely associated with cell-type-specific gene regulation. However, computational tools for detecting FIREs from Hi-C data are still lacking. In this work, we present FIREcaller, a stand-alone, user-friendly R package for detecting FIREs from Hi-C data. FIREcaller takes raw Hi-C contact matrices as input, performs within-sample and cross-sample normalization, and outputs continuous FIRE scores, dichotomous FIREs, and super-FIREs. Applying FIREcaller to Hi-C data from various human tissues, we demonstrate that FIREs and super-FIREs identified, in a tissue-specific manner, are closely related to gene regulation, are enriched for enhancer-promoter (E-P) interactions, tend to overlap with regions exhibiting epigenomic signatures of cis-regulatory roles, and aid the interpretation or GWAS variants.</small>

[https://doi.org/10.1016/j.csbj.2020.12.026](https://doi.org/10.1016/j.csbj.2020.12.026)