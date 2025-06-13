---
layout: publication
title: 'MINT: Mitigating Hallucinations In Large Vision-language Models Via Token Reduction'
authors: Chao Wang, Jianming Yang, Yang Zhou
conference: "Arxiv"
year: 2025
bibkey: wang2025mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.00717"}
tags: ['Transformer', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Multimodal Models']
---
Hallucination has been a long-standing and inevitable problem that hinders
the application of Large Vision-Language Models (LVLMs) in domains that require
high reliability. Various methods focus on improvement depending on data
annotations or training strategies, yet place less emphasis on LLM's inherent
problems. To fill this gap, we delve into the attention mechanism of the
decoding process in the LVLM. Intriguingly, our investigation uncovers the
prevalent attention redundancy within the hierarchical architecture of the
LVLM, manifesting as overextended image processing in deep layers and an
overabundance of non-essential image tokens. Stemming from the observation, we
thus propose MINT, a novel training-free decoding strategy, MItigating
hallucinations via tokeN reducTion. Specifically, we dynamically intensify the
LVLM's local perception capability by masking its attention to irrelevant image
tokens. In addition, we use contrastive decoding that pushes the model to focus
more on those key image regions. Our full method aims to guide the model in
concentrating more on key visual elements during generation. Extensive
experimental results on several popular public benchmarks show that our
approach achieves a 4% improvement in mitigating hallucinations caused by
distracted perception compared to original models. Meanwhile, our approach is
demonstrated to make the model perceive 5% more visual points even though we
reduce a suite of image tokens.
