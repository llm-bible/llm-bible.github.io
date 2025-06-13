---
layout: publication
title: 'Read-only Prompt Optimization For Vision-language Few-shot Learning'
authors: Dongjun Lee, Seokwon Song, Jihee Suh, Joonmyung Choi, Sanghyeok Lee, Hyunwoo J. Kim
conference: "Arxiv"
year: 2023
bibkey: lee2023read
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.14960"}
  - {name: "Code", url: "https://github.com/mlvlab/RPO"}
tags: ['Transformer', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Security', 'Attention Mechanism', 'Has Code', 'Few-Shot', 'Multimodal Models', 'Prompting']
---
In recent years, prompt tuning has proven effective in adapting pre-trained
vision-language models to downstream tasks. These methods aim to adapt the
pre-trained models by introducing learnable prompts while keeping pre-trained
weights frozen. However, learnable prompts can affect the internal
representation within the self-attention module, which may negatively impact
performance variance and generalization, especially in data-deficient settings.
To address these issues, we propose a novel approach, Read-only Prompt
Optimization (RPO). RPO leverages masked attention to prevent the internal
representation shift in the pre-trained model. Further, to facilitate the
optimization of RPO, the read-only prompts are initialized based on special
tokens of the pre-trained model. Our extensive experiments demonstrate that RPO
outperforms CLIP and CoCoOp in base-to-new generalization and domain
generalization while displaying better robustness. Also, the proposed method
achieves better generalization on extremely data-deficient settings, while
improving parameter efficiency and computational overhead. Code is available at
https://github.com/mlvlab/RPO.
