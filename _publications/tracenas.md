---
title: "TraceNAS: Zero-shot LLM Pruning via Gradient Trace Correlation"
collection: publications
category: conferences
permalink: /publications/tracenas
excerpt: ''
date: February, 2026
venue: 'ArXiv Preprint'
# slidesurl: 'https://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/pdf/2602.02891'
bibtexurl: '/files/tracenas.bib'
citation: 'Malettira, P. G., Nagaraj, M., Roy, A., Negi, S., & Roy, K. (2026). TraceNAS: Zero-shot LLM Pruning via Gradient Trace Correlation. arXiv preprint arXiv:2602.02891.'
---
<!-- excerpt: 'A training-free NAS framework for joint LLM depth and width pruning that reduces search overhead by 10x via a novel gradient correlation proxy.' -->
## Abstract
Structured pruning is essential for efficient deployment of Large Language Models (LLMs). The varying sensitivity of LLM sub-blocks to pruning necessitates the identification of optimal non-uniformly pruned models. Existing methods evaluate the importance of layers, attention heads, or weight channels in isolation. Such localized focus ignores the complex global structural dependencies that exist across the model. Training-aware structured pruning addresses global dependencies, but its computational cost can be just as expensive as post-pruning training. To alleviate the computational burden of training-aware pruning and capture global structural dependencies, we propose TraceNAS, a training-free Neural Architecture Search (NAS) framework that jointly explores structured pruning of LLM depth and width. TraceNAS identifies pruned models that maintain a high degree of loss landscape alignment with the pretrained model using a scale-invariant zero-shot proxy, effectively selecting models that exhibit maximal performance potential during post-pruning training. TraceNAS is highly efficient, enabling high-fidelity discovery of pruned models on a single GPU in 8.5 hours, yielding up to 10x reduction in GPU-hours compared to training-aware methods. Evaluations on the Llama and Qwen families demonstrate that TraceNAS is competitive with training-aware baselines across commonsense and reasoning benchmarks.
<!-- The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font. -->
