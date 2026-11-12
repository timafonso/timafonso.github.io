---
title: "Multiple Instance Learning for WSI: A comparative analysis of attention-based approaches"
authors:
- me
- Praphulla M. S. Bhawsar
- Monjoy Saha
- Jonas S. Almeida
- Arlindo L. Oliveira
date: "2024-12-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-12-01T00:00:00Z"

# Publication type.
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Pathology Informatics, 15*, 100403"
publication_short: "*J. Pathol. Inform.*"

abstract: "Whole Slide Images (WSIs) are high-resolution digital scans of microscope slides for which diagnostic and genetic labels are typically recorded at the slide level rather than for individual tiles. We apply weakly supervised Multiple Instance Learning (MIL) to two cancer types from The Cancer Genome Atlas, invasive breast carcinoma (TCGA-BRCA) and lung squamous cell carcinoma (TCGA-LUSC), evaluating tumor detection at low magnification and TP53 mutation detection across several magnifications. We compare Attention MIL (AMIL) and a new Additive MIL (AdMIL) implementation: the additive method matches a reference implementation (AUC 0.96) while Attention MIL performs slightly better (AUC 0.97). The architectures respond to different morphological features at different magnification levels, and TP53 mutation prediction relies most on higher magnifications where cellular structure is most visible. We further use the models' activation scores to produce interpretability heatmaps that highlight regions of interest."

# Summary. An optional shortened abstract.
summary: "A comparison of attention-based Multiple Instance Learning methods (Attention MIL vs. Additive MIL) for tumor and TP53 mutation detection in whole slide images, with interpretability heatmaps for region-of-interest detection."

tags:
- Machine Learning
- Deep Learning
- Medical Imaging
- Explainable AI

featured: false

hugoblox:
  ids:
    doi: 10.1016/j.jpi.2024.100403
    arxiv: "2404.01446"

links:
- type: preprint
  provider: arxiv
  id: "2404.01446"
- type: pdf
  url: https://arxiv.org/pdf/2404.01446

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ""
  focal_point: ""
  preview_only: false

projects: []
slides: ""
---

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
