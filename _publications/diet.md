---
layout: publication_page
show: true
noheader: true

title: "DIETing: Self-Supervised Learning with Instance Discrimination Learns Identifiable Features"
description:

date: 2024-10-01

authors:
  - name: Attila Juhos*
    affiliations: [Max-Planck-Institute for Intelligent Systems, Tübingen]
  - name: <b>Alice Bizeul*</b>
    affiliations: [ETH Zurich, ETH AI Center]
  - name: Patrik Reizinger*
    affiliations: [Max-Planck-Institute for Intelligent Systems, Tübingen]
  - name: David Klindt
    affiliations: [Cold Spring Harbor Laboratory]
  - name: Randall Balestriero
    affiliations: [Brown University]
  - name: Mark Ibrahim
    affiliations: [Facebook AI Research (FAIR)]
  - name: Julia E. Vogt
    affiliations: [ETH Zurich]
  - name: Wieland Brendal 
    affiliations: [Max-Planck-Institute for Intelligent Systems, Tübingen]

journal: UniReps 2024 Neurips Workshop
bib: /assets/bibliography/diet.txt
abstract: Self-Supervised Learning (SSL) methods often consist of elaborate pipelines with hand-crafted data augmentations and computational tricks. However, it is unclear what is the provably minimal set of building blocks that ensures good downstream performance. The recently proposed instance discrimination method, coined DIET, stripped down the SSL pipeline and demonstrated how a simple SSL algorithm can work by predicting the sample index. Our work proves that DIET recovers cluster-based latent representations, while successfully identifying the correct cluster centroids in its classification head. We demonstrate the identifiability of DIET on synthetic data adhering to and violating our assumptions, revealing that the recovery of the cluster centroids is even more robust than the feature recovery.
pdf: /assets/pdf/diet.pdf
arxiv: https://openreview.net/pdf?id=B59jV8cAQq

# Below is an example of injecting additional page-specific styles.
# If you use this page as a template, delete this _styles block.
_styles: >
  # .fake-img {
  #   background: #bbb;
  #   border: 1px solid rgba(0, 0, 0, 0.1);
  #   box-shadow: 0 0px 4px rgba(0, 0, 0, 0.1);
  #   margin-bottom: 12px;
  # }
  # .fake-img p {
  #   font-family: monospace;
  #   color: white;
  #   text-align: left;
  #   margin: 12px 0;
  #   text-align: center;
  #   font-size: 16px;
  # }
---