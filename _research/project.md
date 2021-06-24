---
title: "Sex-specific genetic effects across Biomarkers"
excerpt: "Examination of genetics of 33 biomarker traits in the UK Biobank using Bayesian Mixture Models"
header:
  image: /assets/images/ch3_miami.png
  teaser: /assets/images/ch3_miami.png
gallery:
  - url: /assets/images/ch3_fig1.pdf
    image_path: assets/images/ch3_fig1.pdf
    alt: "Schematic of Sex Effect Mixture Model"
  - url: /assets/images/fig3_betas.pdf
    image_path: assets/images/fig3_betas.pdf
    alt: "Testosterone variants are highly sex-specific"
  - url: /assets/images/ch3_miami.png
    image_path: assets/images/ch3_miami.png
    alt: "Miami plot showing testosterone"
---

This work was done in collaboration with Dr. Manuel Rivas and the [Rivas lab](https://med.stanford.edu/rivaslab.html).

Sex differences are prevalent in many clinical lab values, but the extent to which these differences are due to sex-differential genetic effects is unknown. We developed Sex Effects Mixture Model (SEMM), which is a Bayesian Mixture Model approach, for estimating sex-specific heritability, genetic correlation, and identifying sex-specific variants. We used sex-divided summary statistics from over 300,000 UK Biobank individuals. We found that the majority of the 33 biomarker traits examined did not show sex differences, with the exception of testosterone. For testosterone, we identified many variants with sex-specific effects.

This work was published in the _European Journal of Human Genetics_:
Flynn, E., Tanigawa, Y., Rodriguez, F. et al. Sex-specific genetic effects across biomarkers. Eur J Hum Genet 29, 154–163 (2021). [https://doi.org/10.1038/s41431-020-00712-w](https://www.nature.com/articles/s41431-020-00712-w)

SEMM is available as an R package [here](https://github.com/rivas-lab/semm). This [vignette](https://htmlpreview.github.io/?https://github.com/rivas-lab/semm/blob/dev/doc/semm-vignette.html) demonstrates how the R package is used.

Additionally, the effect sizes of sex-specific testosterone variants are viewable in the Rivas Lab Global Biobank Engine: [https://biobankengine.stanford.edu/sex-effects](https://biobankengine.stanford.edu/sex-effects).

The code used for the publication is included in the repository: [https://github.com/rivas-lab/sex-diff-biomarker-genetics](https://github.com/rivas-lab/sex-diff-biomarker-genetics). 





