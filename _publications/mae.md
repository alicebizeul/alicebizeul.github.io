---
layout: publication_page
show: true
noheader: true

title: "Components Beat Patches: Eigenvector Masking for Visual Representation Learning"
description:

date: 2024-10-01

authors:
  - name: <b>Alice Bizeul</b>
    affiliations: [ETH Zurich, ETH AI Center]
  - name: Thomas Sutter
    affiliations: [ETH Zurich]
  - name: Alain Ryser
    affiliations: [ETH Zurich]
  - name: Julius Von Kügelen
    affiliations: [ETH Zurich]
  - name: Bernhard Schölkopf
    affiliations: [Max Planck Institute for Intelligent Systems]
  - name: Julia E. Vogt
    affiliations: [ETH Zurich]

journal: under submission
bib: /assets/bibliography/mae.txt
abstract: Masked Image Modeling has gained prominence as a powerful self-supervised learning approach for visual representation learning by reconstructing masked-out patches of pixels. However, the use of random spatial masking can lead to failure cases in which the learned features are not predictive of downstream labels. In this work, we introduce a novel masking strategy that targets principal components instead of image patches. The learning task then amounts to reconstructing the information of masked-out principal components. The principal components of a dataset contain more global information than patches, such that the information shared between the masked input and the reconstruction target should involve more high-level variables of interest. This property allows principal components to offer a more meaningful masking space, which manifests in improved quality of the learned representations. We provide empirical evidence across natural and medical datasets and demonstrate substantial improvements in image classification tasks. Our method thus offers a simple and robust data-driven alternative to traditional Masked Image Modelling approaches.
pdf: /assets/pdf/mae.pdf
arxiv: https://openreview.net/forum?id=xqEeGja6zq

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