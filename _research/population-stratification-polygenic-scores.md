---
title: "Population stratification and the limits of polygenic inference"
collection: research
permalink: /research/population-stratification-polygenic-scores
excerpt: "How much population structure survives standard correction in large biobanks, and what the residual does to polygenic scores and tests for selection."
sort_order: 1
---

Genome-wide association studies correct for population structure, almost always with principal component analysis, and polygenic scores are then built from the resulting summary statistics. The correction is treated as adequate. My work asks how adequate it actually is at the scale we now work at — massive biobanks, ancestry-diverse panels, and meta-analyses combining both.

The answer matters because the failure mode is not random noise. Residual ancestry stratification is systematically structured, so it propagates coherently into polygenic scores and into every downstream test built on them, including tests for polygenic adaptation. A signal of selection can be produced by structure that the correction failed to remove.

## Approach

I characterize the limitations of PCA-based correction analytically, drawing on **random matrix theory** to describe the behaviour of the sample covariance eigenstructure in the high-dimensional regime where the number of markers and the sample size grow together. This is the regime real biobanks occupy, and it is one in which intuitions built from small-sample PCA are unreliable.

That theoretical characterization is then paired with empirical evaluation: quantifying the bias that survives correction in real ancestry-diverse panels, and tracing its effect on polygenic score associations and selection tests.

## Why it matters

Polygenic scores are moving into clinical and epidemiological use, and claims about polygenic adaptation in humans have a long history of being confounded by exactly this problem. Knowing the size and structure of the residual bias is a precondition for interpreting either.

## Related work

- Blanc, Mawass & Berg, *Quantifying the susceptibility of polygenic scores to ancestry stratification* (preprint)
- Mawass, Blanc, Sherif & Berg, *Evaluating bias in polygenic score associations due to imperfect control of population stratification* (in preparation)
- Rial, Mawass & Berg, *Information about the derived orientation of disease risk-increasing variants provides power to detect signals of directional selection on diseases* (in preparation)
