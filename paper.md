---
title: 'Longitudinal stability of brain and spinal cord quantitative MRI measures'
tags:
  - quantitative MRI
  - longitudinal stability
  - relaxometry
  - myelin
  - open-source
authors:
  - name: Mathieu Boudreau
    orcid: 0000-0002-7726-4456
    corresponding: true
    affiliation: 1
  - name: Agah Karakuzu
    orcid: 0000-0001-7283-271X
    affiliation: 1
  - name: Arnaud Boré
    orcid: 0000-0002-4822-1211
    affiliation: "2, 3"
  - name: Basile Pinsard
    orcid: 0000-0002-4391-3075
    affiliation: "2, 3"
  - name: Kiril Zelenkovski
    orcid: 0000-0001-7993-7004
    affiliation: 4
  - name: Eva Alonso-Ortiz
    orcid: 0000-0001-6590-7234
    affiliation: "1, 5"
  - name: Julie Boyle
    orcid: 0000-0001-5927-221X
    affiliation: "2, 3"
  - name: Pierre Bellec
    orcid: 0000-0002-9111-0699
    affiliation: "2, 3, 6"
  - name: Julien Cohen-Adad
    orcid: 0000-0003-3662-9532
    affiliation: "1, 3, 5, 7"
affiliations:
 - name: Lyman Spitzer, Jr. Fellow, Princeton University, USA
   index: 1
 - name: Institution Name, Country
   index: 2
 - name: Independent Researcher, Country
   index: 3
date: 13 August 2017
bibliography: paper.bib

# Optional fields if submitting to a AAS journal too, see this blog post:
# https://blog.joss.theoj.org/2018/12/a-new-collaboration-with-aas-publishing
aas-doi: 10.3847/xxxxx <- update this with the DOI from AAS once you know it.
aas-journal: Astrophysical Journal <- The name of the AAS journal.
---

# Summary

Quantitative MRI (qMRI) offers improved specificity, accuracy, and stability compared to qualitative MRI. Longitudinal stability is crucial for reliable measurement of tissue properties in clinical studies. Our study, part of the Courtois project on neural modeling (CNeuroMod), presents initial data from scanning the brains and cervical spinal cords of six participants over several years. We collected three years of data, with up to ten sessions per participant, using qMRI imaging protocols including T1, magnetization transfer (MTR, MTsat), and diffusion. The coefficient of variation (COV) for T1/MTR/MTsat in whole-brain white matter (WM) ranged from 0.6% to 2.3% (intrasubject) and 0.4% to 3.5% (intersubject). For diffusion FA/MD/RD in the corpus callosum regions, the COV ranged from 0.6% to 1.3% (intrasubject) and 3.0% to 10.3% (intersubject). In the spine, the COV for measured spine WM cross-sectional area (CSA) varied between 2.3% and 4.5% (intrasubject) and 5.1% to 9.7% (intersubject) across C2 and C3 vertebral levels. For all qMRI metrics (T1, MTR, MTsat, FA, MD, RD), COVs ranged from 3.9% to 9.5% (intrasubject) and 4.0% to 8.4% (intersubject) across C2 and C5 vertebral levels in the spine. These findings demonstrate the stability of qMRI protocols in the brain and spinal cord, providing valuable insights for future longitudinal clinical studies.

# Statement of need

`Gala` is an Astropy-affiliated Python package for galactic dynamics. Python
enables wrapping low-level languages (e.g., C) for speed without losing
flexibility or ease-of-use in the user-interface. The API for `Gala` was
designed to provide a class-based and user-friendly interface to fast (C or
Cython-optimized) implementations of common operations such as gravitational
potential and force evaluation, orbit integration, dynamical transformations,
and chaos indicators for nonlinear dynamics. `Gala` also relies heavily on and
interfaces well with the implementations of physical units and astronomical
coordinate systems in the `Astropy` package [@astropy] (`astropy.units` and
`astropy.coordinates`).

`Gala` was designed to be used by both astronomical researchers and by
students in courses on gravitational dynamics or astronomy. It has already been
used in a number of scientific publications [@Pearson:2017] and has also been
used in graduate courses on Galactic dynamics to, e.g., provide interactive
visualizations of textbook material [@Binney:2008]. The combination of speed,
design, and support for Astropy functionality in `Gala` will enable exciting
scientific explorations of forthcoming data releases from the *Gaia* mission
[@gaia] by students and experts alike.

# Mathematics

Single dollars ($) are required for inline mathematics e.g. $f(x) = e^{\pi/x}$

Double dollars make self-standing equations:

$$\Theta(x) = \left\{\begin{array}{l}
0\textrm{ if } x < 0\cr
1\textrm{ else}
\end{array}\right.$$

You can also use plain \LaTeX for equations
\begin{equation}\label{eq:fourier}
\hat f(\omega) = \int_{-\infty}^{\infty} f(x) e^{i\omega x} dx
\end{equation}
and refer to \autoref{eq:fourier} from text.

# Citations

Citations to entries in paper.bib should be in
[rMarkdown](http://rmarkdown.rstudio.com/authoring_bibliographies_and_citations.html)
format.

If you want to cite a software repository URL (e.g. something on GitHub without a preferred
citation) then you can do it with the example BibTeX entry below for @fidgit.

For a quick reference, the following citation commands can be used:
- `@author:2001`  ->  "Author et al. (2001)"
- `[@author:2001]` -> "(Author et al., 2001)"
- `[@author1:2001; @author2:2001]` -> "(Author1 et al., 2001; Author2 et al., 2002)"

# Figures

Figures can be included like this:
![Caption for example figure.\label{fig:example}](figure.png)
and referenced from text using \autoref{fig:example}.

Figure sizes can be customized by adding an optional second parameter:
![Caption for example figure.](figure.png){ width=20% }

# Acknowledgements

We acknowledge contributions from Brigitta Sipocz, Syrtis Major, and Semyeong
Oh, and support from Kathryn Johnston during the genesis of this project.

# References
