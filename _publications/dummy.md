---
layout: publication_page
show: true
noheader: true

title: "A Probabilistic Model to Explain Self-Supervised Representation Learning"
description:

date: 2024-02-02

authors:
  - name: <b>Alice Bizeul</b>
    affiliations: [ETH Zurich, ETH AI Center]
  - name: Bernhard Schölkopf
    affiliations: [Max Planck Institute for Intelligent Systems]
  - name: Carl Allen
    affiliations: [ETH Zurich, ETH AI Center]

journal: _under submission_
bib: /assets/bibliography/simvae.txt
abstract: Contrastive learning is a cornerstone underlying recent progress in multi-view and multimodal learning, e.g., in representation learning with image/caption pairs. While its effectiveness is not yet fully understood, a line of recent work reveals that contrastive learning can invert the data generating process and recover ground truth latent factors shared between views. In this work, we present new identifiability results for multimodal contrastive learning, showing that it is possible to recover shared factors in a more general setup than the multi-view setting studied previously. Specifically, we distinguish between the multi-view setting with one generative mechanism (e.g., multiple cameras of the same type) and the multimodal setting that is characterized by distinct mechanisms (e.g., cameras and microphones). Our work generalizes previous identifiability results by redefining the generative process in terms of distinct mechanisms with modality-specific latent variables. We prove that contrastive learning can block-identify latent factors shared between modalities, even when there are nontrivial dependencies between factors. We empirically verify our identifiability results with numerical simulations and corroborate our findings on a complex multimodal dataset of image/text pairs. Zooming out, our work provides a theoretical basis for multimodal representation learning and explains in which settings multimodal contrastive learning can be effective in practice.
pdf: /assets/pdf/iclr2023.pdf
arxiv: https://arxiv.org/pdf/2303.09166.pdf

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