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
 - name: NeuroPoly, Polytechnique Montreal, Montreal, QC, Canada
   index: 1
 - name: Centre de Recherche de l’Institut Universitaire de Gériatrie de Montréal (CRIUGM), Montreal, QC, Canada
   index: 2
 - name: Unité de Neuroimagerie Fonctionnelle (UNF), Centre de Recherche de l’Institut Universitaire de Gériatrie de Montréal (CRIUGM), Montreal, QC, Canada
   index: 3
 - name: Faculty of Computer Science and Engineering (FINKI), Skopje, Macedonia
   index: 4
 - name: Centre de recherche du CHU Sainte-Justine, Université de Montréal, Montreal, QC, Canada
   index: 5
 - name: Psychology Department, Université de Montréal, Montreal, QC, Canada
   index: 6
 - name: Mila - Quebec AI Institute, Montreal, QC, Canada
   index: 7
date: June 14 2023
bibliography: paper.bib
---

# Summary


We present the initial data release of the Courtois project on neural modeling (CNeuroMod), with a specific focus on the quantitative MRI (qMRI) component. The primary objective of this study was to evaluate the longitudinal stability of qMRI measurements in both the brain and cervical spinal cord. 

To achieve this, we conducted regular scanning sessions over a three-year period involving six participants \autoref{fig:figure1}. Each participant underwent up to ten sessions, providing us with a robust dataset. Our brain qMRI imaging protocols consisted of T1, magnetization transfer (MTR, MTsat), and diffusion techniques. In addition to these, the spinal cord imaging protocol included T1w, T2w, and T2\*w cross-sectional area (CSA) measurements.

The results of our study demonstrate the stability of the qMRI protocols used for both the brain and spinal cord. These findings offer valuable insights for the design of future longitudinal clinical studies in this domain. Furthermore, we have developed reproducible and reusable analysis pipelines for structural qMRI of the brain and spinal cord. These pipelines incorporate cutting-edge tools such as FSL, ANTs, qMRLab, and SCT, ensuring robust and accurate analysis.

To enhance the accessibility and dissemination of our work, we have presented our findings as an interactive article using Jupyter Book and Plotly. This format allows for seamless exploration and sharing of the curated findings within an integrated research object. We believe that this approach will facilitate collaboration and encourage further research in the field of qMRI analysis.

Overall, the initial data release of the Courtois project on neural modeling (CNeuroMod), specifically focusing on the quantitative MRI (qMRI) component, provides a significant contribution to the understanding of the longitudinal stability of qMRI measurements in the brain and spinal cord. The study offers valuable insights for future longitudinal clinical studies and establishes reproducible analysis pipelines for structural qMRI. The interactive article format ensures easy accessibility and encourages collaboration among researchers.


# Figures

![Overview of the structural dataset for the Courtois project on neural modelling (CNeuroMod). 6 participants were scanned up to ten times over three years; note that this is an initial data release for 2022, and more scans are regularly being acquired. The structural protocol consists of T1w, T2w and T2\*w scans to quantify brain and SC (including grey matter, GM) morphometry, and MP2RAGE, magnetization transfer (MTR and MTsat), and diffusion-weighted sequences to compute metrics sensitive to demyelination in the white matter (WM).\label{fig:figure1}](featured.png){ width=80% }

# Acknowledgements

The Courtois project on neural modelling was made possible by a generous donation from the Courtois foundation. The Courtois NeuroMod team is based at “Centre de Recherche de l’Institut Universitaire de Gériatrie de Montréal”, with several other institutions involved. See the CNeuromod documentation for an up-to-date list of contributors (https://docs.cneuromod.ca). This study was also funded by the Canada Research Chair in Quantitative Magnetic Resonance Imaging [950-230815], the Canadian Institute of Health Research [CIHR FDN-143263], the Canada Foundation for Innovation [32454, 34824], the Fonds de Recherche du Québec - Santé [322736], the Natural Sciences and Engineering Research Council of Canada [RGPIN-2019-07244], the Canada First Research Excellence Fund (IVADO and TransMedTech), and the Mila - Tech Transfer Funding Program.
