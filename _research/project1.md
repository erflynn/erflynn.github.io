---
title: "Assessing Sex Bias in Transcriptomic Data"
excerpt: "Inferring and assessing sex bias in publicly available expression databases"
header:
  image: /assets/images/sex_breakdown_rb.png
  teaser: /assets/images/sex_breakdown_rb.png
gallery:
  - url: /assets/images/sex_labeling_summary.png
    image_path: assets/images/headshot_dss.png
    alt: "Summary of Sex Labeling"
  - url: /assets/images/headshot_dss.png
    image_path: assets/images/headshot_dss.png
    alt: "Cell line Labels"
  - url: /assets/images/drug_breakdown.png
    image_path: assets/images/drug_breakdown.png
    alt: "Sex breakdown of drug studies"
---

The majority of samples are missing metadata sex labels. To address this issue, we trained models to infer sample sex labels from gene expression data. We then used these labeled to assess sex bias overall, in cell line, and in drug studies. 

This work is published in _BMC Bioinformatics_:
Flynn, E., Chang, A. & Altman, R.B. Large-scale labeling and assessment of sex bias in publicly available expression data. _BMC Bioinformatics_ 22, 168 (2021). [https://doi.org/10.1186/s12859-021-04070-2](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-021-04070-2)

See my repository [https://github.com/erflynn/sl_label](https://github.com/erflynn/sl_label) for the code used to train our sex labeling models and perform downstream analyses.

We are in the process of integrating these labels into the [refine-bio](https://www.refine.bio/) resource so that other researchers have easy access to them.