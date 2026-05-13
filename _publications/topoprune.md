---
title: "TopoPrune: Robust Data Pruning via Unified Latent Space Topology"
collection: publications
category: manuscripts
permalink: /publications/topoprune
excerpt: 'TopoPrune solves the inherent instability of traditional data pruning by using topology to capture the intrinsic, stable structure of a dataset. It creates pruned subsets that are exceptionally robust to noise and highly transferable across different model architectures, even at 90% pruning rates'
date: February, 2026
venue: 'ArXiv Preprint'
bibtexurl: '/files/topoprune.bib'
paperurl: 'https://arxiv.org/pdf/2602.02739'
citation: 'Roy, A., Malettira, P. G., Nagaraj, M., & Roy, K. (2026). TopoPrune: Robust Data Pruning via Unified Latent Space Topology. arXiv preprint arXiv:2602.02739.'
---

## Abstract
Geometric data pruning methods, while practical for leveraging pretrained models, are fundamentally unstable. Their reliance on extrinsic geometry renders them highly sensitive to latent space perturbations, causing performance to degrade during cross-architecture transfer or in the presence of feature noise. We introduce TopoPrune, a framework which resolves this challenge by leveraging topology to capture the stable, intrinsic structure of data. TopoPrune operates at two scales, (1) utilizing a topology-aware manifold approximation to establish a global low-dimensional embedding of the dataset. Subsequently, (2) it employs differentiable persistent homology to perform a local topological optimization on the manifold embeddings, ranking samples by their structural complexity. We demonstrate that our unified dual-scale topological approach ensures high accuracy and precision, particularly at significant dataset pruning rates (e.g., 90%). Furthermore, through the inherent stability properties of topology, TopoPrune is (a) exceptionally robust to noise perturbations of latent feature embeddings and (b) demonstrates superior transferability across diverse network architectures. This study demonstrates a promising avenue towards stable and principled topology-based frameworks for robust data-efficient learning.
<!-- The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font. -->
