---
layout: publication
title: 'Locate-then-merge: Neuron-level Parameter Fusion For Mitigating Catastrophic Forgetting In Multimodal Llms'
authors: Zeping Yu, Sophia Ananiadou
conference: "Arxiv"
year: 2025
bibkey: yu2025locate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.16703"}
tags: ['Multimodal Models', 'Training Techniques', 'Merging', 'Tools']
---
Although multimodal large language models (MLLMs) have achieved impressive performance, the multimodal instruction tuning stage often causes catastrophic forgetting of the base LLM's language ability, even in strong models like Llama3. To address this, we propose Locate-then-Merge, a training-free parameter fusion framework that first locates important parameters and then selectively merges them. We further introduce Neuron-Fusion, a neuron-level strategy that preserves the influence of neurons with large parameter shifts--neurons likely responsible for newly acquired visual capabilities--while attenuating the influence of neurons with smaller changes that likely encode general-purpose language skills. This design enables better retention of visual adaptation while mitigating language degradation. Experiments on 13 benchmarks across both language and visual tasks show that Neuron-Fusion consistently outperforms existing model merging methods. Further analysis reveals that our method effectively reduces context hallucination in generation.
