---
layout: publication
title: 'Aligning Attention Distribution To Information Flow For Hallucination Mitigation In Large Vision-language Models'
authors: Jianfei Zhao, Feng Zhang, Xin Sun, Chong Feng
conference: "Arxiv"
year: 2025
bibkey: zhao2025aligning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.14257'}
tags: ['Attention Mechanism', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning']
---
Due to the unidirectional masking mechanism, Decoder-Only models propagate information from left to right. LVLMs (Large Vision-Language Models) follow the same architecture, with visual information gradually integrated into semantic representations during forward propagation. Through systematic analysis, we observe that over 80% of the visual information is absorbed into the semantic representations. However, the model's attention still predominantly focuses on the visual representations. This misalignment between the attention distribution and the actual information flow undermines the model's visual understanding ability and contributes to hallucinations. To address this issue, we enhance the model's visual understanding by leveraging the core information embedded in semantic representations. Specifically, we identify attention heads that focus on core semantic representations based on their attention distributions. Then, through a two-stage optimization paradigm, we propagate the advantages of these attention heads across the entire model, aligning the attention distribution with the actual information flow. We evaluate our method on three image captioning benchmarks using five different LVLMs, demonstrating its effectiveness in significantly reducing hallucinations. Further experiments reveal a trade-off between reduced hallucinations and richer details. Notably, our method allows for manual adjustment of the model's conservativeness, enabling flexible control to meet diverse real-world requirements. Code will be released once accepted.
