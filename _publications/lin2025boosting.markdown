---
layout: publication
title: 'Aligngen: Boosting Personalized Image Generation With Cross-modality Prior Alignment'
authors: Yiheng Lin, Shifang Zhao, Ting Liu, Xiaochao Qu, Luoqi Liu, Yao Zhao, Yunchao Wei
conference: "Arxiv"
year: 2025
bibkey: lin2025boosting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.21911"}
tags: ['Transformer', 'Efficiency and Optimization', 'Ethics and Bias', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Merging', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Multimodal Models', 'Prompting']
---
Personalized image generation aims to integrate user-provided concepts into text-to-image models, enabling the generation of customized content based on a given prompt. Recent zero-shot approaches, particularly those leveraging diffusion transformers, incorporate reference image information through multi-modal attention mechanism. This integration allows the generated output to be influenced by both the textual prior from the prompt and the visual prior from the reference image. However, we observe that when the prompt and reference image are misaligned, the generated results exhibit a stronger bias toward the textual prior, leading to a significant loss of reference content. To address this issue, we propose AlignGen, a Cross-Modality Prior Alignment mechanism that enhances personalized image generation by: 1) introducing a learnable token to bridge the gap between the textual and visual priors, 2) incorporating a robust training strategy to ensure proper prior alignment, and 3) employing a selective cross-modal attention mask within the multi-modal attention mechanism to further align the priors. Experimental results demonstrate that AlignGen outperforms existing zero-shot methods and even surpasses popular test-time optimization approaches.
