---
layout: publication
title: 'Activation-guided Consensus Merging For Large Language Models'
authors: Yuxuan Yao, Shuqi Liu, Zehua Liu, Qintong Li, Mingyang Liu, Xiongwei Han, Zhijiang Guo, Han Wu, Linqi Song
conference: "Arxiv"
year: 2025
bibkey: yao2025activation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.14009"}
tags: ['Tools', 'Efficiency and Optimization', 'Merging', 'Reinforcement Learning', 'Training Techniques', 'Prompting']
---
Recent research has increasingly focused on reconciling the reasoning capabilities of System 2 with the efficiency of System 1. While existing training-based and prompt-based approaches face significant challenges in terms of efficiency and stability, model merging emerges as a promising strategy to integrate the diverse capabilities of different Large Language Models (LLMs) into a unified model. However, conventional model merging methods often assume uniform importance across layers, overlooking the functional heterogeneity inherent in neural components. To address this limitation, we propose \textbf\{A\}ctivation-Guided \textbf\{C\}onsensus \textbf\{M\}erging (\textbf\{ACM\}), a plug-and-play merging framework that determines layer-specific merging coefficients based on mutual information between activations of pre-trained and fine-tuned models. ACM effectively preserves task-specific capabilities without requiring gradient computations or additional training. Extensive experiments on Long-to-Short (L2S) and general merging tasks demonstrate that ACM consistently outperforms all baseline methods. For instance, in the case of Qwen-7B models, TIES-Merging equipped with ACM achieves a \textbf\{55.3%\} reduction in response length while simultaneously improving reasoning accuracy by \textbf\{1.3\} points. We submit the code with the paper for reproducibility, and it will be publicly available.
