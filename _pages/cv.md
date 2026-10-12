---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<p><a href="{{ base_path }}/files/WalidMawass_CV.pdf" class="btn btn--primary">Download CV (PDF)</a></p>

Education
======
* **Ph.D. in Cellular &amp; Molecular Biology**, Université du Québec à Trois-Rivières (UQTR), Canada — *September 2023*
  Dissertation: *A Quantitative Genetic Study of Life-History Trait Evolution in Preindustrial French-Canadian Populations*
  Advisor: Dr. Emmanuel Milot

* **M.S. in Cellular &amp; Molecular Biology**, Université du Québec à Trois-Rivières — *December 2017*
  Accepted into the Ph.D. program through the fast-track option

* **M1 in Integrative Biology**, Université François-Rabelais, France — *2015*
  Specialization: Behavioral Ecology, Evolution

* **B.S. in Life Sciences**, Lebanese University – Faculty of Sciences II, Lebanon — *August 2014*
  Specialization: Ecology and Biodiversity

Academic Appointments
======
* **Postdoctoral Scholar**, Department of Human Genetics, University of Chicago — *2023–Present*
  Advisor: Dr. Jeremy Berg

* **Postdoctoral Research Associate**, Department of Ecology and Evolutionary Biology, University of Arizona — *2021–2023*
  Advisor: Dr. Joanna Masel

Research Experience
======
**University of Chicago** — Postdoctoral Scholar, *2023–present*
* Characterize the limitations of principal component analysis (PCA) in mitigating population stratification in large-scale genetic association studies across massive biobanks and meta-analyses.
* Formulate analytical frameworks using moment equations and allele frequency spectra to evaluate linked selection, stabilizing selection, and disease-variant evolution.
* Evaluate empirical bias in polygenic score (PGS) selection tests and GWAS summary statistics arising from residual ancestry stratification within ancestry-diverse panels.
* Assess the role of linked selection in shaping genetic diversity patterns in mammalian species, using empirical measurements from monitored wild populations while accounting for recombination and functional target sizes from genomic data.

**University of Arizona** — Postdoctoral Research Associate, *2021–2023*
* Evaluated an analytical model of how a shortage of beneficial mutations determines the long-term evolutionary dynamics of small populations.
* Developed C-based forward-time simulators and HPC pipelines to track long-term mutational dynamics and fitness trajectories across a finite genome with recombination and linkage blocks.
* Quantified the impacts of mutational load and weak epistasis on long-term population fitness under equilibrium dynamics.

**Université du Québec à Trois-Rivières** — Graduate Research Assistant, *2016–2021*
* Processed and analyzed massive retrospective human genealogies comprising millions of individual records to model the long-term inheritance of complex phenotypic traits.
* Applied linear mixed-effects models and variance partitioning to isolate additive genetic variance from complex environmental variation in longitudinal human cohorts.
* Assessed the sensitivity of quantitative genetic parameter estimates to variability in pedigree quality and model specification.

Publications
======
{% assign publications = site.publications | sort: 'sort_order' %}
{% for category in site.publication_category %}
{% assign title_shown = false %}
{% for post in publications %}
{% if post.category != category[0] %}{% continue %}{% endif %}
{% unless title_shown %}
<h3>{{ category[1].title }}</h3>
<ul>
{% assign title_shown = true %}
{% endunless %}
{% include archive-single-cv.html %}
{% endfor %}
{% if title_shown %}</ul>{% endif %}
{% endfor %}

Presentations
======
{% include presentations.html %}

Teaching Experience
======
{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}

Student Mentorship &amp; Advising
======
**Direct Student Research Mentorship**
* **Undergraduate Computer Science Researcher** (University of Arizona, Summer 2022) — Mentored an undergraduate student in translating theoretical population genetics (Wright–Fisher vs. Moran processes, effective population size) into C-based forward-time simulation algorithms.
* **STAR Lab Research Mentor** (University of Arizona, 2022–2023) — Guided undergraduate trainees through hands-on biology projects, from hypothesis generation and literature search to experimental design and implementation.
* **UChicago Computational Biology Outreach (COMBO) Mentor** (2024) — Mentored high school students from underrepresented backgrounds in Python programming, statistical genetics fundamentals, and data analysis.
* **UChicago Berg Lab** (2026) — Mentored a research trainee with a mathematics background on a method development project, engaging weekly with papers, presentations, and technical problems.

**Academic Advising &amp; Evaluation**
* **Grand Award Judge**, SARSEF Regional Science and Engineering Fair (2023) — Evaluated high school and middle school research projects in biology and data science.
* **Evaluator**, Master's &amp; Doctoral Poster Competitions (UQTR, 2019) — Reviewed and scored graduate research presentations, providing structured feedback on scientific rigor and delivery.
* **Student Representative**, Executive Committee for Cellular &amp; Molecular Biology (UQTR, 2019–2021) — Contributed to program reforms and to the development of curriculum courses and their frameworks.

Scholarships &amp; Awards
======
* University of Chicago BSD CAP Travel Award
* Excellence Award, CPCS-BCM
* 1st Prize, Departmental Poster Competition

Leadership, Service &amp; Outreach
======
**Leadership**
* **Co-Chair, Community and Membership Engagement (CME)**, GSA Early Career Leadership Program — *2023–2025*
* **Postdoc Member**, EEB Committee for Community, Anti-Racism, and Equity (CARE), University of Arizona — *2022–2023*
* **VP for Scientific Affairs**, Executive Committee, AEBCM student association, UQTR — *2018–2021*

**Conference Organization**
* WAMBAM — *2017*
* Journées Généalogie et Génétique — *2017*
* SQEBC — *2018*
* MidWest Population Genetics Symposium — *2026*

**Outreach and Service**
* GSA ECLP alumni mentorship program — *2025*
* Grand Award Judge, SARSEF Fair — *2023*
* STAR Lab research mentor — *2022–2023*
* Session chair and moderator, Evolution Conference — *2021*
* UQTR outreach program — *2019*
* Instructor, local scientific outreach program, Lebanon — *2013*

Computer &amp; Statistical Skills
======
* **Programming Languages:** Python (NumPy, SciPy, pandas, scikit-learn), R, SQL, C, Unix Shell, Wolfram/Mathematica
* **Methodologies:** Genome-Wide Association Studies (GWAS), polygenic score (PGS) evaluation, random matrix theory, mixed-effects and multilevel modeling, population stratification correction, high-dimensional variance partitioning
* **Modeling &amp; Simulation:** SLiM, msprime, tree-sequence recording with `tskit`, custom forward-time simulators in C
* **Environments &amp; Workflows:** High-Performance Computing (HPC), Snakemake, Git/GitHub, RStudio, Jupyter
* **Writing &amp; Typesetting:** LaTeX, Markdown, HTML

Scholarly Memberships
======
* American Society of Human Genetics (ASHG)
* Genetics Society of America (GSA)
* Society for Molecular Biology and Evolution (SMBE)
* Society for the Study of Evolution (SSE)
* Society for Modeling and Theory in Population Biology (SMTPB)
* American Genetic Association (AGA)
* National Postdoctoral Association

Languages
======
* **Arabic** — native
* **French** — native
* **English** — full professional proficiency
