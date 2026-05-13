---
title: "TSkips: Efficiency Through Explicit Temporal Delay Connections in Spiking Neural Networks"
collection: publications
category: manuscripts
permalink: /publications/tskips
excerpt: ''
date: 2025-07-03
venue: 'Transactions on Machine Learning Research'
paperurl: 'https://openreview.net/pdf?id=hwz32S06G4'
bibtexurl: '/files/tskips.bib'
citation: 'Malettira, P. G., Negi, S., Ponghiran, W., & Roy, K. (2024). TSkips: Efficiency through explicit temporal delay connections in spiking neural networks. arXiv preprint arXiv:2411.16711.'
---
<!-- excerpt: TSkips introduces a novel architectural mechanism for Spiking Neural Networks (SNNs) that utilizes explicit temporal skip connections to significantly improve inference efficiency and temporal dependency modeling. By allowing information to bypass layers across time steps, the framework achieves state-of-the-art performance on neuromorphic benchmarks while reducing the energy footprint of deep SNNs. -->
## Abstract
Spiking Neural Networks (SNNs) with their bio-inspired Leaky Integrate-and-Fire (LIF) neurons inherently capture temporal information. This makes them well-suited for sequential tasks like processing event-based data from Dynamic Vision Sensors (DVS) and event-based speech tasks. Harnessing the temporal capabilities of SNNs requires mitigating vanishing spikes during training, capturing spatio-temporal patterns and enhancing precise spike timing. To address these challenges, we propose TSkips, augmenting SNN architectures with forward and backward skip connections that incorporate explicit temporal delays. These connections capture long-term spatio-temporal dependencies and facilitate better spike flow over long sequences. The introduction of TSkips creates a vast search space of possible configurations, encompassing skip positions and time delay values. To efficiently navigate this search space, this work leverages training-free Neural Architecture Search (NAS) to identify optimal network structures and corresponding delays. We demonstrate the effectiveness of our approach on four event-based datasets: DSEC-flow for optical flow estimation, DVS128 Gesture for hand gesture recognition and Spiking Heidelberg Digits (SHD) and Spiking Speech Commands (SSC) for speech recognition. Our method achieves significant improvements across these datasets: up to 18% reduction in Average Endpoint Error (AEE) on DSEC-flow, 8% increase in classification accuracy on DVS128 Gesture, and up to 8% and 16% higher classification accuracy on SHD and SSC, respectively.
<!-- Using [MathJax](https://www.mathjax.org/) in the description is supported - $$E=mc^2$$ - however, the use must be mindful that the default delimiters are `$$...$$` and `\\[...\\]` which differs from the `$...$` that is typically expected. -->
