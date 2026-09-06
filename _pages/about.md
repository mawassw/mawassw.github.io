---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome! I'm **Walid Mawass**, an evolutionary geneticist currently a postdoctoral scholar with Jeremy Berg at the University of Chicago. My research studies how population history shapes genetic variation and trait architecture — and what that determines about outcomes. In wild and historical populations those outcomes are **adaptive**: whether a declining population can respond, persist, and recover. In human complex-trait genetics they are **predictive**: whether a polygenic score works for the person it is applied to. The underlying question is the same in both cases. The data, stakes, and audiences differ.

---

## Two Research Programs

### Program I &mdash; Evolutionary Genetics of Adaptation and Persistence

*Relevant to: evolutionary biology, ecology, integrative biology, conservation genetics*

This program asks what constrains evolutionary response in wild and historical populations: can a population adapt in one fitness component while declining in another; how much of its heritable variation can selection actually use; and what does surviving a population crash cost in the direction of remaining variation? I use long-term pedigree records from monitored vertebrate populations and preindustrial human genealogies, forward-time simulations across finite genomes, and analytical quantitative-genetic and allele-frequency frameworks. The conservation implication is concrete: wildlife managers currently lack a way to assess, before intervening through genetic rescue or assisted migration, whether the heritable variation a population carries will respond to the selection it faces.

### Program II &mdash; Population History and Human Genetic Architecture

*Relevant to: genetics, human genetics, genomics, molecular and cell biology*

This program asks what population history did to the variation underlying complex traits that medicine now predicts from: how much sits in rare variants that selection held at low frequency; whether ancestry stratification that survives principal-component correction propagates coherently into polygenic scores and tests for polygenic adaptation; and whether the genetic basis of a trait turns over between populations fast enough that a score trained in one cannot follow it into another. I develop analytical frameworks drawing on random matrix theory, allele frequency spectra, and quantitative genetics, and apply them to biobank-scale GWAS data and cohort records. Failures of polygenic prediction turn out to be partly evolutionary in origin — predictable from demographic history before clinical deployment, not only discoverable from clinical failure afterward.

### What connects them

Population history acts on genetic variation twice: directly, through which variants a population carries and at what frequency; and indirectly, through what demographic events did to the trait's architecture — how variation is distributed across loci, how rare or common, and whether organized in ways selection can use. That dual action is what Program I studies in wild populations trying to adapt, and what Program II studies in clinical genetics trying to predict. The empirical toolkit is the same: pedigree-based quantitative genetics, allele frequency theory, and forward simulation — applied to systems as different as Soay sheep on St Kilda and large-scale GWAS in the UK Biobank.

---

## Selected Research Highlights

- **Mutational drought.** Showed that a shortage of beneficial mutations &mdash; not merely accumulation of deleterious ones &mdash; is the dominant driver of extinction vortices in small populations over long timescales. The mechanism implies that the populations currently classified as genetically stable may already be in the deficit regime; and that genetic rescue strategies need to address the supply of beneficial variation, not only deleterious load. *(Proc. Royal Soc. B, 2026)*

- **Evolutionary non-predictability.** Demonstrated that genotype-by-environment interactions modulate rates of microevolution in human life-history traits, and that replicate populations under consistent selection still reach contrasting evolutionary outcomes &mdash; a violation of the core quantitative-genetic prediction that bounds how far evolutionary forecasting can be pushed in structured populations. *(Evolution, 2022; J. Evol. Biol., 2025; bioRxiv preprint)*

- **Stratification and polygenic scores.** Applied random matrix theory to characterize when PCA correction for population stratification fails &mdash; not when structure is strongest, but where it first becomes detectable &mdash; and developed diagnostics quantifying how much residual stratification survives into polygenic score associations and selection tests. *(bioRxiv preprint; manuscript in preparation)*

- **Heritable fitness variance and neutral diversity.** Developed a theoretical framework linking heritable fitness variance, measured from 19 monitored vertebrate pedigrees, to expected genome-wide neutral diversity through unlinked background selection. The estimates are irreconcilable in both directions &mdash; too small for the observed diversity deficits, too large to sustain under mutation&ndash;selection&ndash;drift balance &mdash; no rescaling resolves both at once. *(Manuscript in preparation)*

For the full list of publications see my [CV](/cv/) or [Publications](/publications/) page.

---

## Methods &amp; Tools

- **Analytical frameworks:** random matrix theory, moment equations, allele frequency spectra, quantitative genetic modeling with pedigree and genomic data
- **Simulation:** forward-time simulators in C, SLiM, msprime, tree-sequence recording with `tskit`
- **Statistical modeling:** Bayesian and mixed-effects models, variance partitioning, population stratification correction in GWAS and PGS analyses
- **Infrastructure:** HPC pipelines, Snakemake, Python (NumPy, SciPy, pandas), R

I value open science and share data, code, and models where possible.

---

## Mentorship &amp; Teaching

I am committed to mentoring students in **quantitative and computational evolutionary biology and genetics**. I have supervised projects from concept to publication, led and co-led graduate seminars, guest-lectured on quantitative genetics, and mentored high school students from underrepresented backgrounds. Research in my group runs on simulation and existing pedigree or genomic datasets, which means it scales to diverse teaching loads and engages undergraduates at well-defined entry points before the full empirical work begins.

---

## Service &amp; Outreach

I have served in leadership roles in the Genetics Society of America's Early Career Leadership Program, facilitated workshops for international students, and mentored high school students in Python, statistical genetics, and data analysis through UChicago's COMBO program. I serve as an ad hoc peer reviewer and have organized and chaired sessions at international conferences including the Evolution Conference.

---

Explore my [research](/research/), [publications](/publications/), [CV](/cv/), [talks](/talks/), [teaching](/teaching/), and [contact information](/contact/). Code and collaborations are on [GitHub](https://github.com/mawassw).
