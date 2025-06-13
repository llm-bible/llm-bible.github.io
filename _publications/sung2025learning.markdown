---
layout: publication
title: 'RSQ: Learning From Important Tokens Leads To Better Quantized Llms'
authors: Yi-lin Sung, Prateek Yadav, Jialu Li, Jaehong Yoon, Mohit Bansal
conference: "Arxiv"
year: 2025
bibkey: sung2025learning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.01820'}
tags: ['Attention Mechanism', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'GPT', 'Tools', 'Quantization']
---
Layer-wise quantization is a key technique for efficiently compressing large
models without expensive retraining. Previous methods typically quantize the
weights of each layer by "uniformly" optimizing the layer reconstruction loss
across all output tokens. However, in this paper, we demonstrate that
better-quantized models can be obtained by prioritizing learning from important
tokens (e.g. which have large attention scores). Building on this finding, we
propose RSQ (Rotate, Scale, then Quantize), which (1) applies rotations
(orthogonal transformation) to the model to mitigate outliers (those with
exceptionally large magnitude), (2) scales the token feature based on its
importance, and (3) quantizes the model using the GPTQ framework with the
second-order statistics computed by scaled tokens. To compute token importance,
we explore both heuristic and dynamic strategies. Based on a thorough analysis
of all approaches, we adopt attention concentration, which uses attention
scores of each token as its importance, as the best approach. We demonstrate
that RSQ consistently outperforms baseline methods across multiple downstream
tasks and three model families: LLaMA3, Mistral, and Qwen2.5. Additionally,
models quantized with RSQ achieve superior performance on long-context tasks,
further highlighting its effectiveness. Lastly, RSQ demonstrates
generalizability across various setups, including different model sizes,
calibration datasets, bit precisions, and quantization methods.
