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
abstract: Self-supervised learning (SSL) learns representations by leveraging an auxiliary unsupervised task, such as classifying semantically related samples, e.g. different data augmentations or modalities. Of the many approaches to SSL, contrastive methods, e.g. SimCLR, CLIP and VicREG, have gained attention for learning representations that achieve downstream performance close to that of supervised learning. However, a theoretical understanding of the mechanism behind these methods eludes. We propose a generative latent variable model for the data and show that several families of discriminative self-supervised algorithms, including contrastive methods, approximately induce its latent structure over representations, providing a unifying theoretical framework. We also justify links to mutual information and the use of a projection head. Fitting our model generatively, as SimVE, improves performance over previous VAE methods on common benchmarks (e.g. FashionMNIST, CIFAR10, CelebA), narrows the gap to discriminative methods on _content_ classification and, as our analysis predicts, outperforms them where _style_ information is required, taking a step toward task-agnostic representations.
pdf: /assets/pdf/simvae.pdf
url: https://arxiv.org/pdf/2402.01399.pdf

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