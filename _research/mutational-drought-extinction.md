---
title: "Mutational drought and the fate of small populations"
collection: research
permalink: /research/mutational-drought-extinction
excerpt: "Small populations are usually thought to decline because deleterious mutations accumulate. The shortage of beneficial mutations turns out to matter more."
sort_order: 2
---

A small population is conventionally understood to be caught in a ratchet: drift overwhelms selection, deleterious mutations fix, mean fitness falls, the population shrinks further, and the process accelerates. This is **mutational meltdown**, and it has shaped how conservation genetics thinks about genetic risk in small populations.

I have argued for a second, distinct mechanism, which we call **mutational drought**. A shrinking population does not only accumulate deleterious variation; it also loses its supply of beneficial mutations. Adaptation and the compensatory substitutions that offset accumulated load both depend on beneficial mutations arriving at a sufficient rate, and that rate scales with population size. The population is starved of the raw material for improvement at exactly the moment it needs it most.

Over long timescales, this shortage turns out to be the stronger driver of decline.

## Approach

Establishing this required simulations that remain faithful over long evolutionary timescales: **forward-time simulators written in C**, run on HPC pipelines, tracking mutational dynamics and fitness trajectories across a finite genome with recombination and linkage blocks. Realistic linkage matters here, because the interference between segregating mutations is part of the mechanism rather than a detail to be abstracted away. Alongside the simulations, I evaluated analytical models of how a beneficial-mutation shortage governs long-term dynamics, and quantified the roles of mutational load and weak epistasis under equilibrium conditions.

## Why it matters

The two mechanisms imply different interventions. If meltdown dominates, the priority is purging or masking deleterious load. If drought dominates, the priority is restoring the supply of beneficial variation — which points toward maintaining or augmenting effective population size and gene flow. Genetic rescue programmes are built on one theory of the vortex; this work suggests the other half has been underweighted.

## Related work

- Mawass, Hernández, Matheson, Berg & Masel, *Extinction vortices are driven more by a shortage of beneficial mutations than by deleterious mutation accumulation*, **Proceedings of the Royal Society B** (2026)
- Hernández, Mawass, Matheson & Masel, *Rare variants drive high variance in human ancestral fitness at mutation-selection-drift balance*, bioRxiv preprint (2026)
- Marcelle, Hernández, Mawass, Gutenkunst & Masel, *High deleterious mutation rate distorts site frequency spectrum in mammals* (in preparation)
