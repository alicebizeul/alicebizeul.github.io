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

journal: under submission
bib: /assets/bibliography/simvae.txt
abstract: In self-supervised learning (SSL), representations are learned via an auxiliary task without annotated labels. A common task is to classify augmentations or different modalities of the data, which share semantic content (e.g. an object in an image) but differ in style (e.g. the object's location). Many approaches to self-supervised learning have been proposed, e.g. SimCLR, CLIP, and VicREG, which have recently gained much attention for their representations achieving downstream performance comparable to supervised learning. However, a theoretical understanding of self-supervised methods eludes. Addressing this, we present a generative latent variable model for self-supervised learning and show that several families of discriminative SSL, including contrastive methods, induce a comparable distribution over representations, providing a unifying theoretical framework for these methods. The proposed model also justifies connections drawn to mutual information and the use of a ``projection head''. Learning representations by fitting the model generatively (termed SimVAE) improves performance over discriminative and other VAE-based methods on simple image benchmarks and significantly narrows the gap between generative and discriminative representation learning in more complex settings. Importantly, as our analysis predicts, SimVAE outperforms self-supervised learning where style information is required, taking an important step toward understanding self-supervised methods and achieving task-agnostic representations
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