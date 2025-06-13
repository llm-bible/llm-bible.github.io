---
layout: publication
title: 'MEDA: Dynamic KV Cache Allocation For Efficient Multimodal Long-context Inference'
authors: Zhongwei Wan, Hui Shen, Xin Wang, Che Liu, Zheda Mai, Mi Zhang
conference: "Arxiv"
year: 2025
bibkey: wan2025dynamic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.17599'}
  - {name: "Code", url: 'https://github.com/AIoT-MLSys-Lab/MEDA'}
tags: ['Attention Mechanism', 'Has Code', 'Efficiency and Optimization', 'Model Architecture', 'Merging', 'Multimodal Models']
---
Long-context Multimodal Large Language Models (MLLMs) that incorporate long
text-image and text-video modalities, demand substantial resources as their
multimodal Key-Value (KV) caches grow with increasing input lengths,
challenging inference efficiency. Existing methods for KV cache compression, in
both text-only and multimodal LLMs, have neglected attention density variations
across layers, thus often adopting uniform or progressive reduction strategies
for layer-wise cache allocation. In this work, we propose MEDA, a dynamic
layer-wise KV cache allocation method for efficient multimodal long-context
inference. As its core, MEDA utilizes cross-modal attention entropy to
determine the KV cache size at each MLLMs layer. Given the dynamically
allocated KV cache size at each layer, MEDA also employs a KV pair selection
scheme to identify which KV pairs to select and a KV pair merging strategy that
merges the selected and non-selected ones to preserve information from the
entire context. MEDA achieves up to 72% KV cache memory reduction and 2.82
times faster decoding speed, while maintaining or enhancing performance on
various multimodal tasks in long-context settings, including multi-images and
long-video scenarios. Our code is released at
https://github.com/AIoT-MLSys-Lab/MEDA.
