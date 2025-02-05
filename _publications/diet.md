---
layout: publication_page
show: true
noheader: true

title: "Cross-Entropy Is All You Need To Invert the Data Generating Process"
description:

date: 2024-10-29

authors:
  - name: Patrik Reizinger*
    affiliations: [Max-Planck-Institute for Intelligent Systems, Tübingen]
  - name: <b>Alice Bizeul*</b>
    affiliations: [ETH Zurich, ETH AI Center]
  - name: Attila Juhos*
    affiliations: [Max-Planck-Institute for Intelligent Systems, Tübingen]
  - name: Julia E. Vogt
    affiliations: [ETH Zurich]
  - name: Randall Balestriero
    affiliations: [Brown University]
  - name: Wieland Brendal 
    affiliations: [Max-Planck-Institute for Intelligent Systems, Tübingen]
  - name: David Klindt
    affiliations: [Cold Spring Harbor Laboratory]

journal: ICLR 2025
bib: /assets/bibliography/diet.txt
abstract: Supervised learning has become a cornerstone of modern machine learning, yet a comprehensive theory explaining its effectiveness remains elusive. Empirical phenomena, such as neural analogy-making and the linear representation hypothesis, suggest that supervised models can learn interpretable factors of variation in a linear fashion. Recent advances in self-supervised learning, particularly nonlinear Independent Component Analysis, have shown that these methods can recover latent structures by inverting the data generating process. We extend these identifiability results to parametric instance discrimination, then show how insights transfer to the ubiquitous setting of supervised learning with cross-entropy minimization. We prove that even in standard classification tasks, models learn representations of ground-truth factors of variation up to a linear transformation. We corroborate our theoretical contribution with a series of empirical studies. First, using simulated data matching our theoretical assumptions, we demonstrate successful disentanglement of latent factors. Second, we show that on DisLib, a widely-used disentanglement benchmark, simple classification tasks recover latent structures up to linear transformations. Finally, we reveal that models trained on ImageNet encode representations that permit linear decoding of proxy factors of variation. Together, our theoretical findings and experiments offer a compelling explanation for recent observations of linear representations, such as superposition in neural networks. This work takes a significant step toward a cohesive theory that accounts for the unreasonable effectiveness of supervised deep learning.
pdf: /assets/pdf/diet.pdf
arxiv: https://arxiv.org/abs/2410.21869

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