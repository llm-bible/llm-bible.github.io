---
layout: publication
title: 'Mitigating Cache Noise In Test-time Adaptation For Large Vision-language Models'
authors: Haotian Zhai, Xinyu Chen, Can Zhang, Tianming Sha, Ruirui Li
conference: "Arxiv"
year: 2025
bibkey: zhai2025mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.18334"}
tags: ['Security', 'Model Architecture', 'Attention Mechanism', 'Multimodal Models']
---
Test-time adaptation (TTA) of visual language models has recently attracted
significant attention as a solution to the performance degradation caused by
distribution shifts in downstream tasks. However, existing cache-based TTA
methods have certain limitations. They mainly rely on the accuracy of cached
feature labels, and the presence of noisy pseudo-labels can cause these
features to deviate from their true distribution. This makes cache retrieval
methods based on similarity matching highly sensitive to outliers or extreme
samples. Moreover, current methods lack effective mechanisms to model class
distributions, which limits their ability to fully exploit the potential of
cached information. To address these challenges, we introduce a comprehensive
and reliable caching mechanism and propose a novel zero-shot TTA method called
"Cache, Residual, Gaussian" (CRG). This method not only employs learnable
residual parameters to better align positive and negative visual prototypes
with text prototypes, thereby optimizing the quality of cached features, but
also incorporates Gaussian Discriminant Analysis (GDA) to dynamically model
intra-class feature distributions, further mitigating the impact of noisy
features. Experimental results on 13 benchmarks demonstrate that CRG
outperforms state-of-the-art TTA methods, showcasing exceptional robustness and
adaptability.
