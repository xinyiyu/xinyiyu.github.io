---
layout: single
title: "Software"
permalink: /software/
author_profile: true
nav: true
---

## NicheScope: Identifying multicellular niches from spatial transcriptomics  
Spatial transcriptomics enables transcriptome-wide measurement with spatial context, but understanding how local multicellular environments regulate cell states remains challenging.
NicheScope addresses this by jointly modeling neighborhood cell-type composition and transcriptome-wide expression to uncover multicellular niches (MCNs) and niche-regulated cell states (NRCSs) from spatial transcriptomics data.
It also enables comprehensive niche characterization: spatial mapping of niche distribution; pathway enrichment and differential gene expression to reveal collective behavior of constituent cell types; LR inference to uncover intercellular communication; and survival analyses linking niches to clinical outcomes.
NicheScope's scalability and robustness have been demonstrated in diverse tissues including lymph node, lung adenocarcinoma, and head and neck cancer.

* GitHub Repository: [NicheScope](https://github.com/xinyiyu/NicheScope)  
* Paper: Xinyi Yu, Xiaomeng Wan, Leqi Tian, Yuheng Chen, Yuyao Liu, Tianwei Yu, Can Yang, Jiashun Xiao (2025).
  NicheScope: identifying multicellular niches and niche-regulated cell states in spatial transcriptomics.
  *Submitted.*

---

## IBSEP: Integrating bulk and single-cell RNA-seq for ct-eQTL prioritization
Cell-type–specific eQTL (ct-eQTL) discovery is essential for interpreting non-coding GWAS signals, while scRNA-seq studies often suffer from limited sample sizes and bulk RNA-seq ignores cellular heterogeneity. 
IBSEP bridges these two types of data to improve ct-eQTL identification.
IBSEP employs a hierarchical linear model that leverages the power of bulk studies and the resolution of single-cell data simultaneously.
It achieves superior performance in identifying ct-eQTLs compared to existing methods and unveils transcriptional regulatory mechanisms specific to cell types, offering deeper insights into the genetic basis of complex diseases at a cellular resolution.

* GitHub Repository: [IBSEP](https://github.com/xinyiyu/IBSEP)  
* Paper: Xinyi Yu, Xianghong Hu, Xiaomeng Wan, Zhiyong Zhang, Xiang Wan, Mingxuan Cai, Tianwei Yu, Jiashun Xiao (2025).
  A unified framework for cell-type-specific eQTL prioritization by integrating bulk and scRNA-seq data.
  *The American Journal of Human Genetics.*

---

## PALM: Prioritizing risk variants with functional annotations
Most GWAS risk variants lie in non-coding regions, making their functional interpretation difficult. 
Leveraging large-scale functional annotations is essential for better interpreting non-coding GWAS SNPs and identifying more genetic risk variants with weak or moderate effects.
PALM is an adaptive latent model for integrating cell-type/tissue-specific functional annotations with GWAS summary statistics to improve risk variant discovery. 
Using a tree-ensemble framework, PALM flexibly captures non-linear relationships between annotations and association status, and scales to millions of variants through a functional-gradient EM algorithm. 
It enhances power, controls FDR, and provides interpretable prioritization of functional annotations across complex traits.

* GitHub Repository: [PALM](https://github.com/YangLabHKUST/PALM)  
* Paper: Xinyi Yu, Jiashun Xiao, Mingxuan Cai, Yuling Jiao, Xiang Wan, Jin Liu, Can Yang (2023).
   PALM: A powerful and adaptive latent model for prioritizing risk variants with functional annotations.
   *Bioinformatics.*
